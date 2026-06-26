# ♟️ Jogo de Damas com Inteligência Artificial

> Um clássico repaginado: jogue contra um AI que pensa com o algoritmo de busca **MiniMax**, implementado do zero em Python usando **PyGame**.

---

## 📌 Sobre o projeto

Este repositório faz parte do trabalho em grupo com o tema **Inteligência Artificial aplicada ao Jogo de Damas**.  
Aqui você encontra um jogo totalmente jogável, com interface gráfica feita no **PyGame**, e um motor de decisão inteligente que analisa movimentos através do algoritmo **MiniMax**.

O que diferencia nosso jogo:

- 🎨 **Interface visual** atraente e responsiva com PyGame.
- 🧠 **IA competitiva** usando MiniMax para decidir jogadas.
- 🔄 Suporte a partidas **Jogador vs Computador**, e boa sorte vencendo esse computador 🙂.
- ⚡ Código limpo e pronto para evoluir.

---

## 🛠️ Tecnologias usadas

- [Python 3.x](https://www.python.org) – linguagem principal.
- [PyGame](https://www.pygame.org/) – criação do tabuleiro, eventos e renderização.
- **MiniMax** – algoritmo de busca para tomada de decisão da IA.

---
## Objetivo

Implementar um Jogo de Damas utilizando um agente inteligente para jogar contra o humano. O Agente Inteligente utilizará uma busca MiniMax para conseguir efetuar as melhores jogadas possíveis e impedir que o jogador ganhe terreno no tabuleiro.

## Metodologia

Estamos utilizando o Python como nossa linguagem principal e o PyGame como nossa Library Auxiliar para a criação do tabuleiro e interatividade do jogador com o mesmo. Além disso, estaremos implementando um Agente com Busca MiniMax, que descreveremos com mais detalhes logo abaixo...

## Busca MiniMax?

A Busca MiniMax é um algoritmo de decisão muito usado para jogos de dois jogadores, como o Jogo da Velha, o Xadrez e as Damas. É uma Árvore de Busca que explora múltiplas jogadas possíveis expandindo nós profundos, alguns deles chegando até o final do jogo. Após expandir os nós, esse algoritmo consegue determinar quais serão as jogadas que levarão o agente ao sucesso de melhor forma, enquanto impede o sucesso do adversário.

## Resultado

Em uma amostragem de cerca de 30 partidas, a IA consistentemente venceu 90% das partidas jogadas. Tendo um pouco mais de dificuldade quando o jogador consegue fazer uma Dama.

---

## 🚀 Como executar o projeto

**1. Clone este repositório**
```sh
https://github.com/LucasSantiago257/ai-checkers.git
cd ai-checkers-unifacs
```

**2. Instale as Dependências**
```sh
pip install -r requirements.txt
```

**3. Execute o Jogo**
```sh
python main.py
```
---

🤖 Funcionamento da IA

> A Inteligência Artificial do jogo segue o algoritmo MiniMax para considerar todos os movimentos possíveis a partir da situação atual do tabuleiro e escolher aquele que maximiza suas chances de vitória e minimiza as do adversário.


Etapas na tomada de decisão:
```
Geração de todos os movimentos válidos.
Simulação e avaliação de cada movimento até uma profundidade definida.
Retorno da jogada mais vantajosa segundo a função de avaliação.
```
---

---
## 🔍 Referências
O código de jogo foi parcialmente inspirado no código do TechWithTim (https://www.youtube.com/watch?v=vnd3RfeG3NM).

