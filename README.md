# Time Series Forecasting using LSTM

This project investigates time series forecasting using Long Short-Term Memory (LSTM) neural networks.

## Objective

Predict IndexC using historical values of:
- IndexA
- IndexB
- IndexC

## Models

Two models were implemented:

1. Initial LSTM Model
2. Improved LSTM Model

## Technologies

- Python
- PyTorch
- Pandas
- NumPy

## Results

The improved model achieved better predictive performance.

| Model | Test Loss |
|------|------|
| Initial LSTM | 0.0153 |
| Improved LSTM | 0.0092 |

## Key Improvements

- Increased hidden size
- Added additional LSTM layer
- Introduced dropout regularization
