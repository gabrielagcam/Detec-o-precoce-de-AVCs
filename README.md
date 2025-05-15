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
  - [x] **XGBoost**

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

- O **XGBOOST (Extreme Gradient Boosting)** é um modelo baseado em árvores de decisão, no qual múltiplas árvores são combinadas de forma sequencial. A cada etapa, uma nova árvore é adicionada ao conjunto com o objetivo de corrigir os erros cometidos pelas anteriores. O modelo final é uma combinação ponderada de todas essas árvores, resultando em uma predição mais precisa e robusta.

## 🔍 Resultados:

<table>
  <thead>
    <tr>
      <th rowspan="2">Modelo</th>
      <th rowspan="2">Acurácia</th>
      <th colspan="2">Precisão</th>
      <th colspan="2">Recall</th>
      <th colspan="2">F1-Score</th>
    </tr>
    <tr>
      <th>Classe 0</th>
      <th>Classe 1</th>
      <th>Classe 0</th>
      <th>Classe 1</th>
      <th>Classe 0</th>
      <th>Classe 1</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Random Forest</td>
      <td>0.99</td>
      <td>1.00</td>
      <td>0.98</td>
      <td>0.98</td>
      <td>1.00</td>
      <td>0.99</td>
      <td>0.99</td>
    </tr>
    <tr>
      <td>SVM</td>
      <td>0.98</td>
      <td>1.00</td>
      <td>0.97</td>
      <td>0.97</td>
      <td>1.00</td>
      <td>0.98</td>
      <td>0.98</td>
    </tr>
    <tr>
      <td>KNN</td>
      <td>0.95</td>
      <td>1.00</td>
      <td>0.90</td>
      <td>0.89</td>
      <td>1.00</td>
      <td>0.94</td>
      <td>0.95</td>
    </tr>
    <tr>
      <td>XGBoost</td>
      <td>0.97</td>
      <td>1.00</td>
      <td>0.95</td>
      <td>0.95</td>
      <td>1.00</td>
      <td>0.97</td>
      <td>0.98</td>
    </tr>
  </tbody>
</table>

