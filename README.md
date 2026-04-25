# Nifty500 ML Stock Prediction

Machine Learning pipeline to classify short-term stock direction across the Nifty500 universe using supervised learning models and walk-forward validation.

## Models Used
- Decision Tree
- Random Forest
- XGBoost

## Validation Framework
- Time-series Walk-Forward Validation
- Fold-by-fold out-of-sample testing
- ROC AUC comparison

## Core Features
The models learned predictive importance from:

- Volatility (20D)
- Volume
- Return windows (1D / 5D)
- Range %
- Moving Averages (SMA / EMA)
- MACD
- RSI

## Key Focus
Rather than maximizing in-sample accuracy, this project emphasizes:

- Robust out-of-sample performance
- Signal ranking quality
- Regime stability
- Reduced look-ahead bias

## Example Outputs
- Feature Importance Analysis
- Decision Tree Structure
- Fold-by-Fold ROC AUC
- Prediction Probability Distribution
- Walk-Forward Stability

## Tools Used
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib

## Author
Navon Shapurkar
