<h1> Space Impact </h1>

<p>Este trabalho foi apresentado como Relatório Final da Disciplina de Computabilidade e Complexidade de Algoritmos do Curso de Ciência da Computação do UDF.</p>
<p>Ministrado pela professora: Kadidja Valeria Reginaldo de Oliveira</p>
<p>E realizado pelo aluno: Mateus Alves Torres</p>
<p>
Este trabalho teve como objetivo desenvolver um algoritmo complexo, utilizando uma linguagem de programação como base, para descrever todas as etapas do processo, registrando o aprendizado e as características do desenvolvimento de um código. Para isso, optou-se por replicar um jogo originalmente desenvolvido para celulares, chamado Space Impact, conferindo-lhe uma identidade própria.</p>
<p>O jogo em questão é centrado em uma nave especial encarregada de defender o planeta contra inimigos alienígenas e seu general. À medida que o jogador derrota os inimigos, acumula pontos que, quanto maiores, tornam os inimigos mais difíceis, culminando no confronto com o general, que desempenha o papel de chefe no jogo.</p>
<p>Para a sua criação, utilizou-se a linguagem JavaScript para a programação e desenvolvimento do código, bem como algumas sprites obtidas do Google Imagens para a elaboração do layout.</p>
<p>Essencialmente, o fundo permanece constante. Na tela inicial, o jogador tem a opção de iniciar o jogo e de ativar ou desativar o som.</p>
<p> A nave principal responde aos movimentos do mouse do jogador, deslocando-se para direita, esquerda, cima e baixo. Com um clique, é possível atirar, sendo também viável atirar enquanto a nave está em movimento. Os inimigos são eliminados com um único tiro, proporcionando 50 pontos por inimigo derrotado. Eles movem-se em linha reta pelo cenário. Em caso de colisão com a sua nave, você sofre dano e perde um coração. A nave possui um total de 3 corações.</p>
<p>Ao atingir a marca de 500 pontos, o jogador avança para a próxima fase. Nessa fase, os inimigos mantêm a mesma movimentação e estrutura de dano da fase anterior, mas agora também disparam projéteis que podem causar dano, retirando 1 coração de vida. No entanto, eles passam a conceder 100 pontos por inimigo derrotado. Ao alcançar 2.000 pontos, a segunda fase se inicia, apresentando inimigos que agora concedem 200 pontos por derrota. Eles mantêm a mesma estrutura de dano, mas sua movimentação torna-se mais desafiadora, ocorrendo na diagonal de cima para baixo e vice-versa.</p>
<p>Após acumular 10.000 pontos, o chefe surge. Seu ataque consiste em um raio de linha reta mantido por um período, enquanto ele se movimenta verticalmente. O chefe possui 100 pontos de vida, e cada tiro acertado pelo jogador reduz 1 ponto de vida. Ao derrotá-lo, o jogo é concluído, permitindo ao jogador reiniciar a partida. Caso o jogador perca as 3 vidas em qualquer fase, ele perde o jogo, mas tem a opção de recomeçar.</p>

