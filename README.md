# 🔌 Energy Forecasting & Anomaly Detection with LSTM

This project applies deep learning techniques to forecast household energy consumption and detect anomalies using multivariate time series data (temperature, humidity, power usage).

## 🚀 Overview

- **Goal**: Predict future energy usage and detect unusual consumption patterns.
- **Approach**: Long Short-Term Memory (LSTM) neural network for sequence modeling.
- **Extras**: Anomaly detection based on prediction residuals.

## 🧠 Machine Learning

- Model: LSTM-based regression (TensorFlow/Keras)
- Inputs: Energy usage (kWh), temperature (°C), humidity (%)
- Output: 1-hour ahead forecast
- Anomalies: Detected using 95th percentile of residuals

## 📊 Tools & Stack

- Python (Colab)
- Pandas, NumPy, Matplotlib, Scikit-learn
- TensorFlow/Keras
- Streamlit (optional for dashboard)

## 📝 Results

- RMSE: _insert value here_
- MAE: _insert value here_
- Detected anomalies: _insert number or sample insight here_

## 📈 Visuals

- Forecast vs. Actual Energy Usage
- Anomaly visualization with residual-based thresholds

## 📂 Structure

