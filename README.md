# Detecção-precoce-de-AVCs

## Descrição:

Este repositório contém um projeto de Machine Learning para a detecção de AVCs (Acidente Vascular Cerebral) utilizando dados do Kaggle e um modelo baseado em Random Forest.

## Dados:

Os dados utilizados foram obtidos no [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) e contêm informações como idade, gênero, histórico de hipertensão, doenças cardíacas, nível de glicose no sangue, entre outras variáveis relevantes.

## Metodologia:

- **Pré-processamento dos dados:** Tratamento de valores nulos, encoding de variáveis categóricas e balanceamento de classes.

- **Divisão dos dados:** Separação entre conjunto de treino e teste.

- **Treinamento:** Modelo Random Forest para classificação utilizando o TensorFlow Decision Forests, e Modelo SVM (Support Vector Machine) utilizando Scikit-Learn

- **Avaliação:** Métricas como acurácia, precisão, recall e F1-score foram utilizadas para medir o desempenho.

## Ferramentas utilizadas:

- **Python** 

- **Pandas & NumPy**

- **Matplotlib & Seaborn**

- **Scikit-learn**

- **TensorFlow**


## Análises de Resultados Preliminares: 

O Random Forest é um modelo de aprendizagem de máquina, muito utilizado em problemas de classificação, que consiste na criação de árvores de decisão, em que cada uma recebe diferentes subconjuntos de amostras e variáveis, de modo que o resultado final é obtido através da combinação dessas árvores.

O SVM (Support Vector Machine) também é um modelo de aprendizagem supervisionada, e tem como objetivo encontrar o hiperplano de separação ideal que maximiza a margem entre as classes. Para encontrar o hiperplano ótimo, ele separa as classes maximizando a margem entre os pontos de diferentes classes mais próximos (vetores de suporte), de modo que os novos pontos são classificados com base em qual lado do hiperplano caem.

No desenvolvimento deste projeto, até o presente momento, foram implementados os algoritmos Random Forest e SVM, em que o SVM com utilização de Grid Search apresenta uma melhor acurácia (0,9808, comparada com 0,9652 de acurácia do RF)

## Próximos Passos:

Implementar outros algoritmos de Machine Learning, como o XBoost e KNN para comparar os resultados obtidos com os do Random Forest e SVM.
 
