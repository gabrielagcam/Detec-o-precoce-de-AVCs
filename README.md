# 🧠 Detecção precoce de AVCs 

## 📌 Descrição:

Este repositório contém um projeto de Machine Learning para a detecção de AVCs (Acidente Vascular Cerebral) utilizando dados do Kaggle e um modelo baseado em Random Forest.

## 📊 Dados:

Os dados utilizados foram obtidos no [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) e contêm informações como idade, gênero, histórico de hipertensão, doenças cardíacas, nível de glicose no sangue, entre outras variáveis relevantes.

## 📝 Metodologia:

- [x] **Pré-processamento dos dados:** Tratamento de valores nulos, encoding de variáveis categóricas e balanceamento de classes.

- [x] **Divisão dos dados:** Separação entre conjunto de treino e teste.

- **Implementação de modelos:**
  - [x] **Random Forest**
  - [x] **SVM**
  - [x] **KNN**
  - [ ] **XGBoost**

- [x] **Análise dos modelos**

## 🛠️ Ferramentas utilizadas:

- **Python** 

- **Pandas & NumPy**

- **Matplotlib & Seaborn**

- **Scikit-learn**

- **TensorFlow**


## 🤖 Descrição dos modelos: 

- O **Random Forest** é um modelo de aprendizagem de máquina, muito utilizado em problemas de classificação, que consiste na criação de árvores de decisão, em que cada uma recebe diferentes subconjuntos de amostras e variáveis, de modo que o resultado final é obtido através da combinação dessas árvores.

- O **SVM (Support Vector Machine)** também é um modelo de aprendizagem supervisionada, e tem como objetivo encontrar o hiperplano de separação ideal que maximiza a margem entre as classes. Para encontrar o hiperplano ótimo, ele separa as classes maximizando a margem entre os pontos de diferentes classes mais próximos (vetores de suporte), de modo que os novos pontos são classificados com base em qual lado do hiperplano caem.

- O **KNN (K-Nearest Neighbors)** é um modelo que, quando precisa fazer uma previsão, calcula a distância (geralmente euclidiana) entre o novo ponto e todos os pontos do conjunto de treino, seleciona os K vizinhos de menor distância e classifica o novo ponto com base na maioria das classes desses vizinhos (voto majoritário).

## 🔍 Resultados:


                           |       Precisão      |       f1-score      |        recall       |  
|  Modelo       | Acurácia | classe 0 | classe 1 | classe 0 | classe 1 | classe 0 | classe 1 | 
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | 
| Random Forest |   0.96   |   1.00   |   0.93   |   0.96   |   0.96   |   0.92   |   1.00   |  
| SVM           |   0.98   |   1.00   |   0.97   |   0.98   |   0.98   |   0.97   |   1.00   |
| KNN           |   0.95   |   1.00   |   0.90   |   0.94   |   0.95   |   0.89   |   1.00   |
