# Auto CartPole
Projeto que utiliza de deep leaning para a criação de uma IA para jogar o jogo da biblioteca gym chamado CartPole (v0)

## Time

||**Membros**|**Email**|**GitHub**|
|:-:|:-:|:-:|:-:|
|![igor](https://user-images.githubusercontent.com/48963026/119209005-dbb85800-ba7a-11eb-9577-225e38f7f292.png)|Igor Lima|igorq937@gmail.com|[@igorq937](https://github.com/igorq937)|
|![thiago](https://user-images.githubusercontent.com/48963026/119209013-e83cb080-ba7a-11eb-8a6d-1a5946a6cf39.png)|Thiago Santos|thiago.lopes.santos.tls@gmail.com|[@thiagolopess](https://github.com/thiagolopess)|

## Bibliotecas Utilizadas

### Gym

Gym é um toolkit para desenvolvimento e aprendizado de algoritmos através de comparação e reforço. Ele suporta o treinamento de Agents seja para ensiná-los a andar ou jogar alguns jogos de maneira independente.

### Tensorflow

TensorFlow é uma biblioteca de código aberto criada para aprendizado de máquina, computação numérica e muitas outras tarefas

### Keras-RL2

O Keras-RL2 implementa algoritmos top de linha para Aprendizado Profundo Através de Reforço(deep reinforcement learning), e se integra com a biblioteca de deep learning Keras.

Mas o que é Deep Reiforcement Learning (Deep RL)?

Deep Reinforcement Learning é um subcampo do machine learning que combina o reinforcement learning (RL) e o deep learning. O RL considera o problema a ser resolvido por um agente computacional de aprendizado e toma decisões baseadas em tentativa e erro. Já o Deep RL incorpora deep learning à solução, possibilitando que os agentes tomem decisões a partir de dados de entrada desestruturados.

## Sobre o jogo

![cartpole](https://rl-book.com/learn/drl/cartpole_coach/images/cartpole_random.gif)

O cartpole foi um jogo criado pelo Gym com o intuito de mostrar como a biblioteca funciona. O objetivo do jogo é manter o palito em pé e o carrinho na tela.  O jogo possui apenas dois inputs (direita e esquerda), que são utilizados para equilibrar o palito. Para ganhar uma rodada, a máquina precisa fazer 200 pontos. Após uma rodada acabar (seja ganhando ou perdendo), uma nova rodada começa logo em seguida.

Decidimos utilizar esse jogo no projeto pois ele é mais rápido e simples de ser treinado, uma vez que a IA não precisará se adaptar a uma grande quantidade de situações.