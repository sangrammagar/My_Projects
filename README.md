# 📊 TSLA Stock Price Prediction using LSTM model

This repository contains deep learning model developed for predicting the stock price of **Tesla Inc. (TSLA)** using historical data. The models are built and evaluated using LSTM model.
## 🧠 Models Implemented

📁 **LSTM_Model**
- Deep learning using LSTM for time series forecasting
- Used sequence data with hourly intervals
- Visualized loss curves and R² during training

## 📈 Dataset

- Source: Yahoo Finance using `yfinance` Python library
- Ticker used: `TSLA`
- Timeframe: Last 720 days with 1-hour interval data

## 📊 Evaluation Metrics

Each model is evaluated using the following:
- ✅ **MAE** – Mean Absolute Error
- ✅ **MSE** – Mean Squared Error
- ✅ **RMSE** – Root Mean Squared Error
- ✅ **R² Score** – Coefficient of Determination
- ✅ **MAPE** – Mean Absolute Percentage Error

## 🔧 Technologies Used

- Python
- Pandas, NumPy, Matplotlib
- Scikit-learn
- TensorFlow / Keras
