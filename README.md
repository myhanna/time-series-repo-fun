##  LSTM-Based Stock Price Forecasting with Python

This repository demonstrates how to use Long Short-Term Memory (LSTM) neural networks for **time series forecasting** of stock closing prices, using [TensorFlow/Keras](https://www.tensorflow.org/), [yfinance](https://github.com/ranaroussi/yfinance), and standard Python libraries. The example provided here predicts the closing price of **BBNI.JK** (Bank Negara Indonesia) stock, but can be adapted to other stocks.

## Features

- Download historical stock data with `yfinance`
- Data preprocessing and visualization
- LSTM model for time series prediction
- Early stopping to avoid overfitting
- Prediction trend analysis (upward, downward, sideways)
- Predict next closing price and forecast future prices