# Equity Momentum Backtest

A systematic equity momentum strategy developed in Python and backtested against SPY.

## Strategy

The strategy:

* Uses a universe of 10 large-cap U.S. equities
* Ranks securities using trailing 252-trading-day returns
* Selects the top 3 securities
* Equal-weights the selected securities
* Rebalances monthly
* Compares performance against SPY

## Performance Metrics

The backtest evaluates:

* Cumulative return
* Annualized return
* Annualized volatility
* Sharpe ratio
* Maximum drawdown

## Tools

* Python
* Pandas
* NumPy
* Matplotlib
* yfinance
* Google Colab

## Files

`Copy_of_Equity_Momentum_Test.ipynb` — Complete backtest, analysis, visualizations, and results.

## Disclaimer

This project is for educational and research purposes. Historical backtest performance does not guarantee future results.
