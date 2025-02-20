# Análise e Previsão de Séries Temporais

Este repositório contém dois notebooks dedicados à análise e previsão de séries temporais utilizando diferentes modelos estatísticos e de aprendizado profundo. O objetivo é comparar a eficácia desses modelos através de métricas de avaliação como MAE (Mean Absolute Error) e MSE (Mean Squared Error).

## Conteúdo

### Notebook 1: Previsão de Ações da Google

- Utiliza dados de preços de ações da Google.
- Aplica o modelo estatístico ARIMA (Box-Jenkins).
- Implementa uma rede neural LSTM para previsão.
- Compara os resultados com um modelo Naïve (ingênuo) como baseline.
- Aplica o modelo híbrido NeuralProphet.
- Avalia os modelos com base nas métricas MAE e MSE.

### Notebook 2: Previsão em Dados com Maior Correlação

- Utiliza uma série temporal mais uniforme e com maior correlação entre as variáveis.
- Repete os experimentos do primeiro notebook:
  - ARIMA (Box-Jenkins)
  - Modelo Naïve
  - NeuralProphet
- Compara o desempenho dos modelos com as mesmas métricas (MAE e MSE).


## Dependências

- Python 3.x
- Pandas
- Numpy
- Statsmodels
- TensorFlow/Keras
- NeuralProphet
- Matplotlib/Seaborn


