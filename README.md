# Modeling na Prática
## Descrição do Projeto
Este projeto foi desenvolvido para criar e testar modelos de machine learning, a fim de identificar o melhor modelo para o problema em questão.

## DataSet Utilizado
O dataset utilizado foi o load_london do SKLEARN.

## Modelos Implementados
Foram definidos três modelos para comparação:

## Regressão Linear do SKLEARN
- Support Vector Regression do SKLEARN
- Decision Tree Regression do XGBoost
- Divisão do DataSet.
  
A divisão do dataset foi feita utilizando o método train_test_split do SKLEARN, com 80% dos dados para treino e 20% para teste.

## Métrica de Avaliação
As métricas de avaliação utilizadas foram o MSE (Mean Squared Error) e o RMSE (Root Mean Squared Error), para penalizar grandes erros de previsão. Ambas foram calculadas utilizando métodos do SKLEARN.

## Resultados
Após a execução dos três modelos com os parâmetros padrão, o modelo que apresentou o melhor desempenho foi o Decision Tree Regression do XGBoost, com os menores valores de MSE e RMSE.

## Otimização de Hiperparâmetros
Para melhorar ainda mais o desempenho do modelo, foi utilizado o GridSearchCV do SKLEARN para encontrar os melhores hiperparâmetros do XGBoost. A otimização resultou em uma redução significativa nos erros de previsão.
