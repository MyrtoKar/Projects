# 🌡️ IoT Sensor Anomaly Detection using LSTM & Azure Data Explorer

This project demonstrates an end-to-end anomaly detection pipeline for IoT sensor data (temperature and humidity) using a multivariate LSTM model. Real-time data is queried from **Azure Data Explorer**, processed using **Python**, and anomalies are detected using **deep learning**.

## 📊 Project Overview

- **Source**: IoT sensors (e.g., DHT22/BME280) streaming to Azure Data Explorer (ADX)
- **Goal**: Predict next temperature reading and detect anomalies
- **Model**: LSTM (Long Short-Term Memory) neural network
- **Approach**: Multivariate time series → Forecasting → Residual anomaly detection

## 🧠 Key Features

- 🔌 Live data ingestion from Azure Data Explorer
- 🔄 Multivariate time series modeling with temperature & humidity
- 🧠 Deep learning model using TensorFlow/Keras
- ⚠️ Anomaly detection via residual analysis
- 📈 Interactive plots of predictions and anomalies

## 🛠️ Technologies Used

| Tool/Library        | Purpose                     |
|---------------------|-----------------------------|
| Python              | Core programming language   |
| Azure Data Explorer | IoT data storage and query  |
| TensorFlow / Keras  | Deep learning framework     |
| Pandas / NumPy      | Data manipulation           |
| Matplotlib          | Visualization               |

## 📂 Project Structure

