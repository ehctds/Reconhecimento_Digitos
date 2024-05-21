Este projeto foi desenvolvido como parte da disciplina de Aprendizagem de Máquina do curso de Ciência de dados e IA na Universidade Federal da Paraíba. O objetivo é implementar classificadores de dígitos manuscritos utilizando três modelos lineares de aprendizagem de máquina: Perceptron, Regressão Linear e Regressão Logística. O dataset utilizado é uma versão adaptada do famoso MNIST.

Conteúdo
1. Introdução
O reconhecimento de dígitos escritos a mão é um problema clássico na visão computacional. Utilizamos o dataset MNIST adaptado para classificar os dígitos 0, 1, 4 e 5.

2. Dataset MNIST Adaptado
Imagens em escala de cinza de 28x28 pixels.
Treinamento: train.csv e test.csv com 785 colunas (784 pixels + 1 rótulo).

3. Descrição das Atividades

   3.1 Redução da Dimensão das Amostras
  Reduzir a complexidade dos dados de entrada sintetizando a intensidade e a simetria da imagem.
  Gerar arquivos train_redu.csv e test_redu.csv com as colunas: label, intensidade e simetria.

   3.2 Classificação dos Dígitos 1 x 5
  Filtro dos dados para imagens dos dígitos 1 e 5.
  Treinamento e teste dos três classificadores com os dados filtrados.
  Plotagem dos dados e geração de matrizes de confusão.

   3.3 Classificador de Dígitos Completo
  Implementação da estratégia "um contra todos" para classificar os quatro dígitos.
  Construção de três funções hipótese para a classificação multiclasse.
  3.4 Comparação entre os Classificadores
  Implementação da estratégia "um contra todos" para cada classificador.
  Construção de matrizes de confusão e relatórios de eficácia (acurácia, precisão, recall e F1 score).

Resultados: 

![image](https://github.com/ehctds/Reconhecimento_Digitos/assets/100098820/0ebd054f-9296-4f7e-947f-dbc5a886289b)

![image](https://github.com/ehctds/Reconhecimento_Digitos/assets/100098820/7cb2c51a-80aa-41b5-b89d-be484f4a5624)

![image](https://github.com/ehctds/Reconhecimento_Digitos/assets/100098820/da539c40-e394-4451-92ac-9e37eb498c90)


