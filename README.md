# 🌦️ Weather Forecasting via Time Series (LSTM & ConvLSTM)

A time series forecasting project to predict future weather conditions (e.g. temperature, humidity) using LSTM-based deep learning models.

---

## 🚀 Project Overview
Seq‑to‑one forecasting: use past T timesteps to predict next timestep of target weather feature.

---

## 📁 Dataset
Features include temperature, humidity, pressure, wind speed…
Organized as time‑serie CSV with timestamps.

---

## 🏗️ Models
- Simple LSTM model (e.g. 32 units + Dense)
- Optional ConvLSTM or multi‑step LSTM
- Windowing: past 120 hours → next hour prediction

---

## 📊 Metrics
- MAE & MSE
- Visual plots comparing predictions to actual values

---

## ⚙️ Installation

git clone ...
pip install -r requirements.txt

## ⭐ Acknowledgements
Kaggle Time Series tutorial notebooks
Keras LSTM example weather forecasting
Benchmark datasets like WeatherBench
