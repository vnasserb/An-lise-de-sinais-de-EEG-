# Análise de sinais de EEG para identificação de emoções
Neste projeto, utilizamos a linguagem de programação Python para processar um conjunto de sinais de Eletroencefalograma (EEG) amostrados e utilizá-los como entrada para um conjunto de diferentes modelos de classificação, que decidirão se um determinado sinal é correspondente a uma emoção positiva ou negativa.

- **Caracterização dos sinais**
  - Parâmetros de Hjorth: São parâmetros estatíticos que caracterizam um sinal de EEG.
  - Higher Order Crossings: Este processo consiste em aplicar filtros de diferentes ordens sobre um sinal (que alteram sua amplitude e frequência) e contar quantas vezes o sinal modificado cruza o zero. 

- **Classificadores**
  - A ideia é encontrar os parâmetros que maximizam a acurácia para os modelos SVM, KNN, Random Forest, Regressão Logística e Redes Neurais Artificiais, checando quais deles obtiveram o melhor desempenho. 
