# Energy Consumption Time Series Forecasting

This repository contains time series forecasting models for predicting energy consumption. The goal is to optimize energy distribution networks and improve operational efficiency by accurately forecasting future energy demand. Using historical data, these models capture trends, seasonality, and complex patterns, enabling informed decision-making for resource allocation and infrastructure planning.

---

## Dataset

The dataset is sourced from the **International Energy Agency (IEA)** monthly electricity statistics. It includes:

- Net electricity production  
- Electricity used for pumped storage  
- Distribution losses  
- Other relevant attributes for energy consumption analysis  

---

## Models Implemented

1. **ARMA (AutoRegressive Moving Average)**  
   A classical time series model that uses past values and lagged errors to forecast future energy consumption.

2. **LSTM (Long Short-Term Memory)** *(Work in progress)*  
   A deep learning model that captures long-term dependencies in sequential data using recurrent neural networks with memory cells.

3. **SARIMA (Seasonal AutoRegressive Integrated Moving Average)** *(Work in progress)*  
   A seasonal time series model that incorporates autoregressive, moving average, and seasonal components to predict energy consumption patterns.

---

## Requirements

- Python 3.7 or later  
- Libraries:
  - NumPy
  - Pandas
  - Statsmodels
  - TensorFlow (for LSTM)
  - Matplotlib
  - Seaborn (optional, for visualization)

---

## Usage

1. Ensure the dataset is available in the specified format.  
2. Adapt the code if needed to match your dataset.  
3. Run the notebook to train models, forecast energy consumption, and visualize results.  

---

## Goal

This project demonstrates the application of numerical data modeling and time series forecasting techniques to real-world energy data, providing actionable insights for energy management and infrastructure planning.
