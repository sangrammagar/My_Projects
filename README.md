# PROJECT-1
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
=================================================================================================================================================================================================== 
# PROJECT 2

### 📊 AAPL Stock Price Prediction using LSTM Model

This repository contains a deep learning model developed for predicting the stock price of **Apple Inc. (AAPL)** using historical data. The project uses **Long Short-Term Memory (LSTM)** networks to model and forecast stock prices based on past trends.

### 🧠 Models Implemented

📁 LSTM_Model

* Deep learning using LSTM for **time series forecasting**
* Trained on **sequential data** derived from historical Apple stock prices
* Visualized training and validation loss curves
* Plotted actual vs. predicted values to evaluate model performance
### 📈 Dataset

* **Source**: CSV file (uploaded dataset)
* **Company**: Apple Inc. (AAPL)
* **Timeframe**: May 2015 to May 2020
* **Features used**: `Close`, `Open`, `High`, `Low`, `Volume`, etc.

### 📊 Evaluation Metrics

The performance of the model is assessed using:

* ✅ **MAE** – Mean Absolute Error
* ✅ **MSE** – Mean Squared Error
* ✅ **RMSE** – Root Mean Squared Error
* ✅ **R² Score** – Coefficient of Determination
* ✅ **MAPE** – Mean Absolute Percentage Error

### 🔧 Technologies Used

* 🐍 **Python**
* 📊 **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
* 📚 **Scikit-learn**
* 🔁 **TensorFlow / Keras**
