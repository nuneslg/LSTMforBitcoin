# 📈 Previsão do Valor de Fechamento do Bitcoin com LSTM

Este projeto utiliza uma Rede Neural Recorrente do tipo LSTM (Long Short-Term Memory) para prever os valores de fechamento do Bitcoin com base em dados históricos. A implementação foi feita em Python utilizando a biblioteca Keras com backend TensorFlow.

## 🧠 Objetivo

O objetivo do projeto é aplicar técnicas de Deep Learning para prever o valor futuro de fechamento do Bitcoin, tratando-o como uma série temporal. Este projeto pode servir como base para aplicações mais amplas em previsão de preços de ativos financeiros.

## ⚙️ Tecnologias Utilizadas

- Python
- Google Colab
- TensorFlow / Keras
- Pandas / NumPy / Matplotlib / Scikit-learn

## 📊 Etapas Realizadas

1. **Pré-processamento dos Dados**:
   - Normalização dos valores
   - Janela deslizante para construir sequências de entrada
2. **Construção do Modelo LSTM**:
   - Arquitetura many-to-one para prever o próximo valor
   - Camadas LSTM + Dense
3. **Treinamento**:
   - Validação com conjunto de dados separado
   - Otimização de hiperparâmetros como taxa de aprendizado e número de épocas
4. **Avaliação**:
   - MSE
   - RMSE
   - POCID
   - Gráficos de previsão vs valores reais

## 🖼 Resultados

- O modelo demonstrou capacidade de capturar padrões temporais nos dados históricos do Bitcoin.
- As previsões foram visualizadas e comparadas com os valores reais de fechamento para avaliar a acurácia.

## 🚀 Como Executar

Você pode executar o notebook diretamente no [Google Colab](https://colab.research.google.com/drive/1-j-iYnGVurse-tk0E2kQv5eCO5pu9goB?usp=sharing) da seguinte forma:

1. Faça upload do notebook e dos dados.
2. Execute célula por célula.
3. Modifique hiperparâmetros conforme necessário.

## 📌 Requisitos

- Python 3.7+
- TensorFlow 2.x
- Google Colab (recomendado)

---

> *Este projeto é acadêmico e não constitui recomendação financeira.*
