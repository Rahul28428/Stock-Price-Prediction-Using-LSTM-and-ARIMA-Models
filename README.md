# Stock Price Prediction Using LSTM and ARIMA Models

## Overview
This project implements a stock price prediction model using Long Short-Term Memory (LSTM) and AutoRegressive Integrated Moving Average (ARIMA) algorithms. The goal is to forecast stock prices based on historical data.

## Features
- Fetch historical stock data using Yahoo Finance API.
- Visualize historical closing prices using Plotly.
- Implement LSTM model for time series forecasting.
- Validate predictions using ARIMA model.
- Evaluate model performance with Mean Squared Error (MSE) and information criteria like AIC and BIC.

## Dependencies
- Python 3.x
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - plotly
  - scikit-learn
  - keras
  - statsmodels
  - yfinance
  - pmdarima

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/stock-price-prediction.git
cd stock-price-prediction
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Run the ipynb notebook or Python script to execute the project:
```bash
stock_market_prediction.py
```

2. View results:
- The script will download data, preprocess it, train the LSTM model, evaluate predictions with ARIMA, and visualize results using Plotly.

## Results
- **LSTM Model Performance:**
- Training set MSE: 9.95
- Test set MSE: 36.63

- **ARIMA Model Metrics:**
- AIC: 10231.79
- BIC: 10395.04

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Inspired by similar projects and tutorials.

