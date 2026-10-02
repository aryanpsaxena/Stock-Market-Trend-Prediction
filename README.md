# Deep Learning Mini Project (ICT-4442)
## Stock Market Trend Prediction Using Long Short-Term Memory (LSTM) Networks

* **Student Name:** Aryan Saxena
* **Registration Number:** 220953552
* **Institution:** Manipal Institute of Technology (MIT), MAHE

---

### **Project Overview**
This project implements a robust sequence-modeling pipeline for financial time-series forecasting on the **NIFTY 50** index. The pipeline handles data ingestion via `yfinance`, technical indicator feature engineering (RSI, MACD, EMA, SMA), 3D sliding-window tensor shaping, and a classical machine learning baseline (**XGBoost**) compared against a random-walk persistence model.

### **Directory Structure**
* `notebooks/` - Contains the Google Colab execution files (`.ipynb`).
* `README.md` - Project documentation.

### **Current Phase (Interim Milestone)**
* Data ingestion pipeline & cleaning.
* Technical feature engineering.
* XGBoost baseline evaluation.
* **Next Phase:** Stacked Bidirectional LSTM (BiLSTM) development and Optuna hyperparameter optimization.
