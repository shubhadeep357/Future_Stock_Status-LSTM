<h1 align="center">The Future of Stocks</h1>

<p align="center">
  <img src="image_stock.jpeg" alt="Stock Market Prediction" />
</p>



# 📈 Stock Price Prediction using LSTM (Multi-Feature + Indicators)

This project demonstrates how to forecast stock closing prices using **LSTM (Long Short-Term Memory)** networks, while leveraging both raw stock market features and **technical indicators** commonly used in real-world trading strategies.

---

## 🔍 Project Overview

We aim to model stock price behavior by learning from historical data including Open, High, Low, Close, Volume, and derived indicators like **RSI**, **MACD**, and **Moving Averages**. The LSTM model helps capture temporal patterns in financial time series data and gives insight into trend prediction.

This project serves as a strong base for further experimentation with quantitative financial models.

---

## 🧾 Features Used

The model doesn't rely on a single column. It takes advantage of:

- `Open`
- `High`
- `Low`
- `Close`
- `Volume`
- `RSI (Relative Strength Index)`
- `MACD (Moving Average Convergence Divergence)`
- `MA_20 (20-day Moving Average)`

All features are **normalized** before being fed to the LSTM.

---

## 🧠 Model Architecture

- 2 LSTM Layers (50 units each)
- Dropout for regularization (optional to add)
- Dense layer for final output
- Loss function: Mean Squared Error (MSE)
- Optimizer: Adam

We use a **60-day sliding window** to predict the next day’s closing price.

---

## 🧪 Evaluation

The model is evaluated using:

- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**
- **Visual plots**: Actual vs Predicted values

> While this is not meant for real-time financial advice, it highlights how ML can approximate market behavior.

---

