# Ensaio em algoritmos de Machine Learning de Regressão, Classificação e Clusterização

![Image1](/fundamento_machine_learning/img/kmeans.png)

## Problema de Negócio

<p>A empresa Data Money acredita que a expertise no treinamento e ajuste fino dos algoritmos, feito
pelos Cientistas de Dados da empresa, é a principal motivo dos ótimos resultados que as
consultorias vem entregando aos seus clientes.</p>

## O Desafio

<p>O objetivo desse projeto será realizar ensaios com algoritmos de Classificação, Regressão e
Clusterização, para estudar a mudança do comportamento da performance, a medida que os
valores dos principais parâmetros de controle de overfitting e underfitting mudam.</p>

## Planejamento da Solução

<p>O produto final uma análise mostrando a performance dos algoritmos, avaliados usando múltiplas
métricas, para 3 conjuntos de dados diferentes: Treinamento, validação e teste.</p>

### Algoritmos Ensaidos

#### Classificação

**Algoritmos**: KNN, Decision Tree, Random Forest e Logistic Regression
**Métricas de performance**: Accuracy, Precision, Recall e F1-Score


#### Regressão

**Algoritmos**: Decision Tree Regressor, Random Forest Regressor, Polinomial Regression, 
   Linear Regression Lasso, Linear Regression Ridge, Linear Regression Elastic Net,
**Métricas de performance**: R2, MSE, RMSE, MAE e MAPE

#### Clusterização

**Algoritmos**: K-Means e Affinity Propagation
**Métricas de performance**: Silhouette Score

## Resultados Obtidos

### Clusterização

<p>Foram avaliados 2 algoritmos de Clusterização: KMEANS e Affinity Propagation</p>

#### KMEANS

**O Algortimo KMeans apresentou melhor Silhouette Score com 3 clusters**

![Image2](/fundamento_machine_learning/img/ensaios.jpg)

#### Affinity Propagation

**Com Affinity Propagation o melhor Silhouette Score encontrado foi com o parâmetro preference = -50, onde foram encontrados 7 clusters**

![Image3](/fundamento_machine_learning/img/affinity.png)

### Classificação

Dentre todas as métricas de Classificação o Algoritmo **KNN** foi o único que apresentou queda brusca de performance em relação aos dados de Treino, Validação e Teste.

Os demais algoritmos mantiveram um equilíbrio de performance, mostrando um **poder maior de generalização** 

![Image4](/fundamento_machine_learning/img/classificacao.png)

### Regressão

Dentre os Algoritmos de Regressão, o que teve melhor performance em todas as métricas foi a **Random Forest Regressor**

![Image5](/fundamento_machine_learning/img/regression.png)



