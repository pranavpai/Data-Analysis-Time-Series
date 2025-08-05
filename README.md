# Data-Analysis-Time-Series
Predicting Stock Market Prices using Time Series Analysis

## Overview
This project implements time series analysis to predict BAJAJ Finance stock prices using ARIMA modeling with feature engineering techniques.

## Dataset
- **Source**: BAJAJ Finance stock market data (2000-2018)
- **Features**: Date, Open, High, Low, Close, VWAP, Volume, Turnover, Trades, etc.
- **Records**: 2,291 trading days after data cleaning

## Key Features
- Time series data preprocessing and cleaning
- Feature engineering with rolling statistics (3-day and 7-day windows)
- Auto ARIMA model implementation using pmdarima
- Stock price prediction with VWAP (Volume Weighted Average Price) as target
- Model evaluation with RMSE and MAE metrics

## Files
- `Time_Series_StockPrice.ipynb` - Main analysis and modeling notebook
- `BAJFINANCE.csv` - Historical stock market data
- `README.md` - Project documentation

## Requirements
- pandas
- numpy  
- pmdarima
- scikit-learn
- matplotlib

## Results
The Auto ARIMA model achieves:
- RMSE: 187.75
- MAE: 124.64

The model demonstrates effective stock price prediction capabilities with clear trend following.
