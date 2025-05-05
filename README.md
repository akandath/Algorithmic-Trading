# Algorithmic Trading using Unsupervised Learning

## 📈 Overview

This project replicates the methodology presented in the [YouTube video on Machine Learning & Quant Strategies](https://www.youtube.com/watch?v=9Y3yaoi9rUQ), focusing on unsupervised learning techniques for algorithmic trading. The notebook implements a pipeline to fetch stock data, engineer technical indicators, and use clustering algorithms to form trading strategies.

## 🧠 Techniques Used

- **Data Collection**: Pulls 10 years of historical data for S&P 500 stocks using `yfinance`.
- **Feature Engineering**: Calculates indicators including:
  - Garman-Klass Volatility
  - RSI
  - Bollinger Bands
  - ATR
  - MACD
  - Dollar Volume
- **Modeling**: Applies unsupervised learning (e.g., K-Means clustering) to identify stock groupings and generate trading signals.

## 📂 Structure

- `algorithmic_trading.ipynb`: Main Jupyter notebook containing the full data pipeline, clustering model, and evaluation.
