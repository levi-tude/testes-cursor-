# Jogo da Cobrinha - Morango Edition

Um jogo da cobrinha feito em **HTML, CSS e JavaScript puro** (sem bibliotecas), com visual estilizado, placar em tempo real e sistema de recorde salvo no navegador.

## O que tem no jogo

- Cobra com estilo visual (gradientes e cabeca desenhada)
- Comida em formato de **morango**
- **Placar** durante a partida
- **Recorde** persistente com `localStorage`
- Controles por teclado (setas e WASD)
- Botao de pausar/continuar
- Tela de inicio e fim de jogo

## Como jogar

1. Abra o `index.html` no navegador.
2. Clique em **Iniciar / Reiniciar**.
3. Use as teclas:
   - **Setas** (↑ ↓ ← →) ou **WASD** para mover
   - **Espaco** para pausar/continuar
4. Coma os morangos para crescer e aumentar o placar.
5. Evite bater nas paredes ou no proprio corpo.

## Sistema de placar e recorde

- Cada morango comido vale **1 ponto**.
- O recorde aparece no topo da tela.
- Quando voce bate o recorde, ele e salvo automaticamente no navegador.
- Mesmo fechando a aba, o recorde permanece salvo (ate limpar os dados do navegador).

## Estrutura do projeto

- `index.html`: contem HTML + CSS + JavaScript do jogo.
- `README.md`: documentacao do projeto.

## Executar localmente

Como e um projeto estatico, basta abrir o arquivo `index.html`.

Opcionalmente, voce pode usar um servidor local simples.

Exemplo com Node.js:

```bash
npx serve .
```

Depois, abra o endereco mostrado no terminal.

## Link para jogar

https://rawcdn.githack.com/levi-tude/testes-cursor-/cursor/jogo-da-cobrinha-estilizado-6030/index.html

---

Feito para praticar logica de programacao e manipulacao de canvas no navegador.
