# 🎈 Mundo dos Jogos

Jogos educativos em português para crianças por volta dos 5 anos. Funciona no navegador do computador e no Safari/Chrome do iPhone, **sem instalar nada e sem internet** depois de aberto.

## Jogos incluídos

| Jogo | O que treina |
|---|---|
| 🔤 **Letras e Sons** | Reconhecer letras e o som inicial das palavras (dois modos: achar a letra ou achar a figura) |
| 🔢 **Contar** | Contagem de 1 a 10 com objetos organizados em fileiras de 5 |
| 🎨 **Cores e Formas** | 8 cores e 7 formas geométricas |
| 🧠 **Memória** | 6 pares de bichinhos para achar |

## Recursos pensados para criança pequena

- **Narração em português** — o jogo lê a instrução em voz alta (usa a voz do próprio aparelho). Dá para desligar no botão 🔊 do menu e repetir a instrução no botão 🔁.
- **Botões grandes** e alvos de toque generosos, sem textos longos.
- **Sem punição** — errar não tira ponto nem encerra a rodada; a criança tenta de novo.
- Efeitos sonoros, confete e tela de troféu no final.
- Sem zoom acidental por duplo toque, sem anúncios, sem coleta de dados, sem rede.

## Como usar

**No computador:** abra o `index.html` no navegador (duplo clique).

**No iPhone:** abra o link publicado no Safari → botão Compartilhar → **Adicionar à Tela de Início**. Ele passa a abrir em tela cheia, como um app.

> Observação: em iPhone, a voz e os sons só começam a funcionar depois do primeiro toque na tela (é uma regra do próprio iOS). Por isso a primeira tela tem o botão "Começar".

## Publicar no GitHub Pages

1. Crie um repositório novo (ex.: `jogos-kids`), público.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. No repositório: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `/ (root)` → Save**.
4. Em 1–2 minutos o endereço fica disponível em:
   `https://SEU-USUARIO.github.io/jogos-kids/`

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

- `PALAVRAS` — lista de letra + emoji + palavra do jogo de letras
- `OBJETOS` — figuras usadas no jogo de contar
- `CORES` e `FORMAS` — paleta e formas geométricas
- `TOTAL_RODADAS` — quantas perguntas por partida (padrão: 8)
- `ELOGIOS` / `ANIMOS` — frases de acerto e de erro
