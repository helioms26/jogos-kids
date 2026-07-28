# 🎈 Mundo dos Jogos

Jogos educativos em português, divididos por faixa etária. Funciona no navegador do computador e no Safari/Chrome do iPhone, **sem instalar nada e sem internet** depois de aberto.

👉 **Jogar:** https://helioms26.github.io/jogos-kids/

## 🧸 5 a 7 anos

| Jogo | O que treina |
|---|---|
| 🔤 **Letras e Sons** | Reconhecer letras e o som inicial das palavras |
| 🔢 **Contar** | Contagem de 1 a 10, com objetos em fileiras de 5 |
| 🎨 **Cores e Formas** | 8 cores e 7 formas geométricas |
| 🔁 **O que vem depois?** | Padrões e sequências (AB, AAB, ABC, ABB) |
| ➕ **Somar até 10** | Soma visual juntando dois grupos |
| 🧠 **Memória** | 6 pares de bichinhos |
| 🚗 **Corrida** | Coordenação e ritmo — toque rápido para vencer o rival |
| 🧩 **Quebra-cabeça** | Montar figuras 3×3 trocando peças de lugar |
| 🎯 **Mira Certeira** | Atenção e reflexo — 12 alvos |

## 🚀 8 a 11 anos

| Jogo | O que treina |
|---|---|
| ✖️ **Tabuada** | Multiplicação do 2 ao 10 |
| 🧮 **Contas Rápidas** | Soma, subtração, multiplicação e divisão |
| 🔡 **Palavra Embaralhada** | Ortografia — montar a palavra letra a letra |
| 📈 **Sequência Numérica** | Progressões, dobros, quadrados e Fibonacci |
| 🌎 **Quiz Rápido** | Geografia, ciências, corpo humano e cultura geral |
| 🧠 **Memória Turbo** | 8 pares |
| 🏎️ **Corrida Turbo** | Mesma corrida, com rival mais rápido |
| 🧩 **Quebra-cabeça** | Figuras 4×4 |
| 🎯 **Mira Turbo** | Alvos menores e mais rápidos, com bombas para evitar |

## Recursos

- **Narração em português (voz feminina)** — o jogo lê a instrução em voz alta usando a voz do próprio aparelho. Ele escolhe automaticamente a melhor voz pt-BR disponível (prioriza versões "Enhanced/Neural" e vozes femininas como Luciana ou Google português do Brasil), e um seletor 🎙️ no menu permite trocar. O botão 🔊 liga/desliga e o 🔁 repete a instrução.
- **Botões grandes** e alvos de toque generosos, sem textos longos.
- **Sem punição** — errar não tira ponto nem encerra a rodada (exceto a bomba do Mira Turbo, que tira 1 estrela).
- Efeitos sonoros, confete e tela de troféu no final.
- Sem zoom acidental por duplo toque, sem anúncios, sem coleta de dados, sem rede.

## Como usar

**No computador:** abra o `index.html` no navegador (duplo clique).

**No iPhone:** abra o link no Safari → botão Compartilhar → **Adicionar à Tela de Início**. Ele passa a abrir em tela cheia, como um app.

> Em iPhone, a voz e os sons só começam a funcionar depois do primeiro toque na tela (regra do próprio iOS) — por isso a primeira tela tem o botão "Começar".
> Se a voz soar robótica, vá em *Ajustes → Acessibilidade → Conteúdo Falado → Vozes → Português (Brasil)* e baixe a voz **Luciana (Aprimorada/Premium)**. Depois escolha-a no seletor 🎙️ do menu.

## Sobre o conteúdo do Quiz

As perguntas usam fatos escolares consolidados (capitais brasileiras, Sistema Solar, corpo humano, geometria, cultura geral). Vale conferir antes de usar em contexto escolar — a lista fica no array `QUIZ` dentro do `index.html`.

## Arquivos

```
index.html            → o jogo inteiro (HTML + CSS + JS num arquivo só)
manifest.json         → permite "instalar" na tela de início
apple-touch-icon.png  → ícone no iPhone
icon-192.png / icon-512.png → ícones do manifest
.nojekyll             → evita o GitHub Pages processar os arquivos
```

## Personalizar

Tudo fica no `index.html`:

- `CATALOGO` — lista de jogos, ícone, cor, faixa etária e nº de rodadas
- `PALAVRAS` / `PALAVRAS_GRANDES` — palavras dos jogos de letras e anagrama
- `QUIZ` — perguntas e respostas
- `CENAS` — figuras SVG do quebra-cabeça
- `CORES` e `FORMAS` — paleta e formas geométricas
- `ELOGIOS` / `ANIMOS` — frases de acerto e de erro
