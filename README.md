# CP2 - SERS

## Integrantes
* Felipe Mitsuo Takahashi Stephano RM570692
* Laura Godoy Callegari — RM569181
* Letícia Araújo Espindola — RM569308
* Milena de Aguiar Lopes Cardoso — RM570599
* Mariana Dreset Carbollan RM569207

## Objetivo

Treinar um modelo de classificação para prever se uma rede elétrica está **estável** ou **instável**, utilizando o algoritmo de **Regressão Logística**.

## Dataset

O dataset possui 10.000 registros e 14 colunas. A variável alvo é `stabf`, com as classes `stable` e `unstable`.

As features utilizadas são os demais atributos, com exceção de `stab` e `stabf`.

## Etapas

* Carregamento e inspeção dos dados
* Separação das features e do target
* Separação dos dados em treino e teste
* Treinamento do modelo
* Geração das previsões
* Avaliação dos resultados

## Algoritmo

* Regressão Logística (`LogisticRegression`)

## Métricas

* Acurácia
* Precisão
* Matriz de confusão

## Tecnologias

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Execução

O projeto pode ser executado pelo **Google Colab** ou em um ambiente Python com as bibliotecas util
