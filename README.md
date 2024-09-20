# Stock Trading Strategy Backtester

A Python-based tool that backtests multiple trading strategies on historical stock market data, including RSI, Moving Average, Breakout, and Momentum strategies. The tool fetches historical data using the `yfinance` library, applies trading strategies, backtests the performance, and provides detailed performance summaries.

## Features

- Fetch historical stock data from Yahoo Finance using `yfinance`
- Apply multiple technical trading strategies, including:
  - **RSI Strategy** (Relative Strength Index)
  - **Moving Average Crossover Strategy** (SMA50 and SMA200)
  - **Breakout Strategy** (using 20-day high/low breakouts)
  - **Momentum Strategy** (based on 12-period momentum)
- Backtest the performance of the strategies on training and testing data splits
- Visualize cumulative returns for each strategy
- Summarize key performance metrics, such as total return, buy/sell signals
