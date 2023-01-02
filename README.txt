Fala galera!!

Hoje estou trazendo códigos para tratamento de dados e criação de modelo e previsões usando Random Forest e Redes Neurais.

Random Forest
1 - Verifiquei se existem dados nulos, nesse caso não tinha.
2 - Agrupei as colunas individualmente para verificar se existem valores fora do padrão.
3 - Separei os previsores e a classe.
4 - Fiz um Label Encoder nos previsores.
5 - Separei os dados para treinamento e teste.
6 - Criei o modelo de Random Forest com o que separei para treinamento.
7 - Fiz a previsão com o que separei para teste.
8 - Fiz a matrix confusão e consegui uma taxa de acerto de 76%

Redes Neurais
1 - O inicio é quase o mesmo, porém fiz um Label Encoder também na classe.
2 - Fiz uma escala para transformar os dados em float
3 - Preparei o modelo com a 20 neurônios de entrada, inicializador Uniform e ativação Relu
4 - Segunda camada com os mesmos parâmetros.
5 - Terceira camada com 1 neurônio de saída, inicializador Uniform e ativação Sigmoid
6 - Usei binary_crossentropy no loss
7 - Treinei o modelo com 1000 epochs, com validação e callback.
8 - Consegui uma taxa de acerto de 77%.
