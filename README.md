# RNA_Classificadores
Este é um exemplo de código em Python que utiliza a biblioteca scikit-learn para treinar modelos de rede neural MLP (Multilayer Perceptron) para classificação do famoso conjunto de dados Iris.

## Requisitos
Python 3.x
Bibliotecas Python: scikit-learn, matplotlib
## Descrição
O código realiza o seguinte:

1. Carrega o conjunto de dados Iris usando sklearn.datasets.load_iris.

2. Divide os dados em features e target.

3. Treina um modelo MLPClassifier usando as features e o target original.

4. Realiza previsões com o modelo treinado e plota um gráfico de dispersão mostrando as previsões e os rótulos originais.

5. Realiza uma análise de PCA (Análise de Componentes Principais) para reduzir a dimensionalidade das features para 2 componentes principais.

6. Treina outro modelo MLPClassifier usando as features PCA transformadas.

7. Realiza previsões com o modelo PCA treinado e plota um gráfico de dispersão mostrando as previsões e os rótulos originais no espaço PCA.

8. Plota a matriz de confusão para avaliar o desempenho dos modelos.

## Resultados
O código exibirá gráficos de dispersão mostrando a classificação dos dados, tanto no espaço de features original quanto no espaço PCA, bem como as matrizes de confusão para avaliação dos modelos.

## Autor
Vinicius Moura Rodrigues
