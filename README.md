# ML-Stock-Forecasting

# Walk-Forward Machine Learning Model for Equity Returns

This project implements a Python-based machine learning pipeline to forecast
next-day equity returns using historical market data.

The model uses engineered technical features and is evaluated using walk-forward
validation to avoid look-ahead bias. Predictions are converted into a simple
trading strategy and assessed through backtesting against a buy-and-hold
benchmark.

## Methods
- Feature engineering: momentum, volatility, trend, volume
- Models: Ridge Regression, Random Forest
- Validation: TimeSeriesSplit (walk-forward)
- Evaluation: MAE, RMSE, directional accuracy, Sharpe ratio

## Tools
Python, pandas, NumPy, scikit-learn, yfinance, matplotlib
