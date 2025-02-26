# Análise e predição de valores de ações

## Introdução

Notebook feito com o intuito de expor conhecimentos de aprendizado de máquina na prática para fazer análise e predição de valores de ações da bolsa de valores. Primeiro fazemos exploração dos dados usando gráficos para visualizar a variação dos valores, média movel, risco ao investir e descobrir a correlação entre as ações analizadas, para assim fazer o pré processamento dos dados para treinar o modelo [Long Short-Term Memory layer (LSTM)](https://keras.io/api/layers/recurrent_layers/lstm/) para prever seus possíveis valores ao longo do tempo.

## Instruções para rodar o notebook

### Pré requisitos
- [Docker](https://www.docker.com/)
- VScode com a extensão [Dev Container](https://code.visualstudio.com/docs/devcontainers/containers)

### Rodar projeto
1. Clonar repositório na sua máquina

2. Quando solicitado, reabra o projeto no container

3. Abrar o notebook `main.ipynb`

4. Rode as células para executar o código

## Referências e links úteis para se aprofundar

[Arquitetura de Redes Neurais Long Short Term Memory (LSTM)](https://www.deeplearningbook.com.br/arquitetura-de-redes-neurais-long-short-term-memory/)

Vídeo [Long Short-Term Memory (LSTM), claramente explicado](https://www.youtube.com/watch?v=YCzL96nL7j0)

Vídeos sobre cuidados ao usar LSTM ao prever valores de ações: 
1. [Predicting Stock Prices with LSTMs: One Mistake Everyone Makes (Episode 16)](https://www.youtube.com/watch?v=Vfx1L2jh2Ng)
2. [Stock Price Prediction with Machine Learning Mistakes: Prices As Inputs (Episode 20)](https://www.youtube.com/watch?v=aIklUbW0UWI)
3. [Common Mistakes in Stock Price Prediction: Prices As Targets (Episode 21)](https://www.youtube.com/watch?v=xOcyV5Q2G5I)

Notebook usado como Base [📊Stock Market Analysis 📈 + Prediction using LSTM](https://www.kaggle.com/code/faressayah/stock-market-analysis-prediction-using-lstm)

[biblioteca do Yahoo finance para obter dados financeiros](https://aroussi.com/post/python-yahoo-finance)