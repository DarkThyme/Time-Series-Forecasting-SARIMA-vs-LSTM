# Time-Series-Forecasting-SARIMA-vs-LSTM
This repo compares SARIMA and LSTM models for predicting fruit prices using historical data. It includes data preprocessing, seasonal analysis, and forecasting future prices (e.g., Banana prices in Feb 2025). Results are evaluated using MAE and RMSE metrics.

# 📈 Time Series Forecasting: SARIMA vs LSTM on Fruit Prices 🍌🍎  

This repository contains a Jupyter Notebook that implements **Time Series Forecasting** using **SARIMA** and **LSTM** models to predict fruit prices, specifically focusing on **Banana prices in February 2025**. The dataset is sourced from the **Kalimati Tarkari Market**, and the models are trained on historical price trends.

## **🛠️ Models Used**
1. **SARIMA (Seasonal AutoRegressive Integrated Moving Average)**
   - Captures seasonal trends using statistical methods.
   - Tuned hyperparameters: `(p,d,q) x (P,D,Q,s) = (1,1,1) x (0,1,1,12)`

2. **LSTM (Long Short-Term Memory - Deep Learning)**
   - Captures complex price patterns using a neural network.
   - Uses multiple layers with dropout for better generalization.

## **📊 Performance Metrics**
| Model  | MAE  | RMSE  |
|--------|------|-------|
| **SARIMA** | `17.49` | `23.71` |
| **LSTM** | `4.39` | `7.18` |

## **📅 Predictions for February 2025**
The notebook forecasts **Banana prices** for **February 2025**, comparing **SARIMA and LSTM** results. 

## **🚀 How to Run**
1. Clone the repository:  
   ```bash
   git clone https://github.com/DarkThyme/Time-Series-Forecasting-SARIMA-vs-LSTM.git
