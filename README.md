# Genius — Jogo da Memória

Uma versão simples do clássico jogo de memória "Genius".

Um jogo leve feito com Pygame: observe a sequência de cores e repita usando as setas do teclado ou clicando nos setores com o mouse.

## Features

- Sequências geradas aleatoriamente que aumentam de nível.
- Feedback visual (flash) e sons por cor (se os arquivos estiverem em `./assets`).
- Controles por teclado e mouse.

## Como funciona

1. Pressione ESPAÇO para iniciar o jogo.
2. O jogo mostra uma sequência de cores (observe).
3. Repita a sequência usando as setas (ou clicando nos setores): se acertar, avança ao próximo nível; se errar, fim de jogo.

## Controles (teclas)

- CIMA    = Azul
- ESQUERDA = Verde
- BAIXO   = Amarelo
- DIREITA = Vermelho
- ESPAÇO  = Iniciar / Reiniciar
- ESC     = Sair do jogo

Também é possível clicar com o mouse sobre os setores circulares para entrar as cores durante a fase de entrada.

## Requisitos

- Python 3.8+
- Pygame

Instale o pygame com pip:

```fish
python3 -m pip install pygame
```

## Como executar

```fish
python3 genius_game.py
```

Observações:

- Coloque arquivos de som em `./assets` com nomes `red.wav`, `green.wav`, `blue.wav`, `yellow.wav` e `game_over.wav` para habilitar os efeitos sonoros. O jogo funciona sem sons (apenas mostrará avisos no terminal).
- O jogo abre em tela cheia por padrão.

Bom jogo! :) 
