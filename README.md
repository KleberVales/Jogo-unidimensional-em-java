# Jogo unidimensional em java
O jogo funciona da seguinte forma:

Você está parado no índice 𝑖 de um array de 𝑛 elementos chamado game. A partir de algum índice 𝑖 (onde 0 ≤ 𝑖 < 𝑛), você pode realizar um dos seguintes movimentos:
- Mover para trás: Se a célula 𝑖 − 1 existir e contiver um 0, você pode voltar para a célula 𝑖 − 1.
- Mover para frente:
  * Se a célula 𝑖 + 1 contiver um 0, você pode caminhar até a célula 𝑖 + 1.
  * Se a célula 𝑖 + 𝑙𝑒𝑎𝑝 contiver um 0, você pode pular até a célula 𝑖 + 𝑙𝑒𝑎𝑝.
- Se você estiver na célula 𝑖 ou se o valor de 𝑖 + 𝑙𝑒𝑎𝑝 for maior ou igual a 𝑛, você pode sair do final do array e vencer o jogo.

Em outras palavras, você pode se mover do índice 𝑖 para 𝑖 + 1, 𝑖 − 1, ou 𝑖 + 𝑙𝑒𝑎𝑝, desde que o destino seja uma célula contendo um 0. Se o índice de destino for maior ou igual a 𝑛, você vence o jogo.
