# Titanic
Este projeto é baseado no **[desafio Titanic disponível no Kaggle](https://www.kaggle.com/c/titanic)**, que propõe uma análise e previsão de sobrevivência de passageiros com base em diversas variáveis.

Os resultados podem ser acessados ​​no Kaggle.


## [Etapa 1: Primeiro modelo](https://github.com/letibraga/Titanic/blob/main/Parte%201.ipynb)
- Nesta etapa, realizamos procedimentos básicos para avaliar o desempenho sem aplicar tratamentos avançados ou engenharia de dados.
- Eliminamos colunas com alta cardinalidade, tratamos valores ausentes usando média e modas, e removemos todas as colunas de texto.
- Implementamos modelos usando três algoritmos: Árvore de texto Classificação, KNN e Regressão Logística, avaliando-os por meio de acurácia e matriz de confusão.

A ***pontuação pública retornada pelo Kaggle foi de 0,66746.***

## [Etapa 2: Segundo modelo](https://github.com/letibraga/Titanic/blob/main/Parte%202.ipynb)
- Na segunda etapa, nos concentramos principalmente no tratamento das variáveis ​​de texto para incorporar todas as informações em nosso modelo.
- Para realizar esse processo, aplicamos as funções lambda e o OneHotEncoder.
- Mantivemos os mesmos modelos usados ​​anteriormente

A ***pontuação pública retornada pelo Kaggle foi de 0,76555.***
