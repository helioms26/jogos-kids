# 🎈 Mundo dos Jogos

23 jogos educativos em português, divididos por faixa etária. Funciona no navegador do computador e no Safari/Chrome do iPhone, **sem instalar nada e sem internet** depois de aberto. Tudo em um único arquivo `index.html`, sem bibliotecas externas.

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
| 🎯 **Estilingue** | Física e pontaria — derrube os porquinhos (estilo Angry Birds) |
| 💥 **Duelo de Canhões** | Mire e acerte o robô antes que ele te acerte — 3 dificuldades |
| 💄 **Salão de Beleza** | Cabelo, maquiagem e rosto — atenda o pedido do cliente |

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
| 🎯 **Estilingue Turbo** | Estruturas mais altas e porquinhos mais resistentes |
| 💥 **Duelo Turbo** | Mesmo duelo, com o robô ainda mais preciso |
| 💄 **Salão de Beleza** | Pedidos com 3 itens (cabelo, batom e enfeite) |
| 🔠 **Jogo da Forca** | Vocabulário e ortografia — 6 palavras com dica de categoria |

## Como funcionam os jogos de física

**Estilingue** e **Duelo de Canhões** usam um motor de física próprio, escrito do zero neste
arquivo: caixas com gravidade, colisões resolvidas por impulso, atrito, e destruição por
impacto (blocos e porquinhos quebram quando levam uma pancada forte). Ao puxar para mirar,
aparece a linha pontilhada da trajetória — a mesma matemática que o robô adversário usa
para calcular os tiros dele.

O Duelo começa com a escolha da dificuldade:

| Nível | Erro de mira do robô | Corações |
|---|---|---|
| 😀 **Fácil** | erra bastante | você 4 · robô 2 |
| 😎 **Médio** | duelo parelho | você 3 · robô 3 |
| 😈 **Difícil** | quase não erra | você 3 · robô 4 |

Durante o duelo o placar mostra, o tempo todo, **quantos acertos faltam para cada lado vencer**,
de quem é a vez, e os corações desenhados em cima de cada torre. O botão *Trocar dificuldade*
volta para a escolha a qualquer momento.

## Salão de Beleza

Cada cliente chega **suja e despenteada**, e a rodada tem duas partes:

**1. 🛁 Banho — de esfregar, não de clicar.** São cinco etapas e em todas a criança
**arrasta o dedo sobre o rosto** para trabalhar: 🚿 molhar (as gotas vão aparecendo) →
🧴 shampoo (a espuma vai crescendo) → 🚿 enxaguar (a espuma e a sujeira vão saindo) →
🌬️ secar (as gotas vão sumindo) → 🪮 pentear (os fios espetados vão baixando). A ferramenta
segue o dedo, uma barra mostra o progresso e o som (ruído branco filtrado, gerado na hora)
toca enquanto está esfregando. Um toque simples também rende progresso, para quem usa mouse.
O botão **🔄 Refazer banho** volta tudo ao início.

**2. 💄 Visual** — rosto em SVG com 5 tons de pele, 6 cortes de cabelo, 8 cores de cabelo,
6 cores de olho, 6 batons, sombra, blush, 5 enfeites e 5 fundos.

**O pedido é mostrado em desenho e cor, não só em texto** — pensado para quem ainda não lê.
Cada item vira uma fichinha com o ícone da categoria e uma **amostra visual**: bolinha da cor
pedida, o emoji do enfeite ou um **desenho do corte de cabelo**. As abas correspondentes ficam
com um anel amarelo, e a fichinha marca ✅ sozinha quando aquele item é atendido. Tocar na
fichinha leva direto para a aba certa. Os cortes de cabelo também aparecem como desenhos reais
do penteado, em vez de emoji.

Os pedidos **variam a cada cliente**: sorteiam 2 itens (5–7 anos) ou 3 (8–11) de uma fila
embaralhada com 9 categorias — corte, cor do cabelo, batom, sombra, blush, cor dos olhos,
enfeite, fundo e tom de pele — sempre com um valor diferente do atual. O **✨ Pronto!** só
pontua quando tudo confere, e errando ele leva direto para a aba do que falta. O **🔄 Refazer**
apaga o visual para começar de novo, o **🛁 Banho** repete o banho e o **📷 Salvar** baixa
o resultado como PNG.

## Jogo da Forca

Versão leve da brincadeira clássica: 6 palavras por partida, cada uma com uma dica de
categoria (animal, comida, lugar, objeto, natureza, esporte) e 6 tentativas erradas. O
bonequinho aparece **pendurado na barra pelas mãos, sorrindo** — a estrutura do jogo é a
mesma, sem a imagem do enforcamento. As palavras são todas sem acento, para o teclado
ficar simples. Se acabar as chances, a palavra é revelada antes de seguir.

## Recursos

- **Narração em português (voz feminina)** — o jogo lê as instruções em voz alta usando a voz
  do próprio aparelho, e escolhe sozinho a melhor pt-BR disponível. O botão 🎙️ do menu abre uma
  tela onde dá para **ouvir cada voz antes de escolher**, com selo de qualidade
  (✨ Aprimorada · 🌐 Online · 🔈 Padrão · 📻 Comprimida), ajustar a velocidade
  (🐢 devagar / 🙂 normal / 🐇 rápida) e ver o passo a passo de como instalar uma voz melhor
  no próprio aparelho. O 🔊 do menu liga/desliga a narração e o 🔁 repete a instrução.
- **Botão de som 🔊 dentro de cada jogo** — desliga na hora todos os efeitos sonoros e a
  narração (útil em sala de espera, carro ou na hora de dormir). O estado vale para todos os
  jogos até ser religado.
- **Botões grandes** e alvos de toque generosos, sem textos longos.
- **Sem punição** — errar não tira ponto nem encerra a rodada.
- Efeitos sonoros, confete e tela de troféu no final.
- Sem zoom acidental por duplo toque, sem anúncios, sem coleta de dados, sem rede.

## Como usar

**No computador:** abra o `index.html` no navegador (duplo clique).

**No iPhone:** abra o link no Safari → botão Compartilhar → **Adicionar à Tela de Início**.
Ele passa a abrir em tela cheia, como um app.

> Em iPhone, a voz e os sons só começam a funcionar depois do primeiro toque na tela (regra do
> próprio iOS) — por isso a primeira tela tem o botão "Começar".

### Por que a voz soa robótica (e como resolver)

O navegador não sintetiza voz: ele só pede para o **sistema operacional** falar. Quem define a
qualidade é a voz instalada no aparelho, e nenhum site consegue melhorar isso por conta própria.
O que o jogo faz é escolher a melhor voz disponível e falar com prosódia natural (ritmo perto de
1.0 e tom perto de 1.0 — tom agudo é justamente o que dá a sensação de robô nas vozes compactas).

Para a diferença grande, instale uma voz melhor — a tela 🎙️ mostra o caminho certo para o seu
aparelho:

- **iPhone/iPad:** Ajustes → Acessibilidade → Conteúdo Falado → Vozes → Português (Brasil) →
  baixar **Luciana (Aprimorada)** ou **(Premium)**. A que já vem instalada é a comprimida.
- **Android:** Configurações → Sistema → Idiomas → Saída de texto para voz → Serviço de voz do
  Google + dados de voz em Português (Brasil).
- **Windows:** Configurações → Hora e Idioma → Fala → Adicionar vozes → Português (Brasil).
  No Chrome, as vozes **Google** (🌐 Online) são as mais naturais.

## Sobre o conteúdo do Quiz

As perguntas usam fatos escolares consolidados (capitais brasileiras, Sistema Solar, corpo
humano, geometria, cultura geral). Vale conferir antes de usar em contexto escolar — a lista
fica no array `QUIZ` dentro do `index.html`.

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
- `montarFase()` — as 3 fases do Estilingue (blocos e porquinhos)
- `FORCA_EST` / `FORCA_DUELO` — força do lançamento; `GRAV` — gravidade
- `erroV` / `erroA` em `tiroDoRobo()` — pontaria do robô no Duelo
- `velRival` em `novaCorrida()` — velocidade do rival na Corrida
- `CORES_CABELO`, `CORES_BATOM`, `PELES`, `ACESSORIOS` — opções do Salão
- `PALAVRAS_FORCA` — palavras e dicas do Jogo da Forca (sempre sem acento)
- `ELOGIOS` / `ANIMOS` — frases de acerto e de erro
