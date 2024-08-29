Portfolio Optimization Script
Overview
This script optimizes a stock portfolio by maximizing the Sharpe Ratio using historical data from Yahoo Finance (yfinance). Users input stock symbols, and the script calculates the optimal weights for the portfolio.

Requirements
You'll need the following Python libraries:

pandas
numpy
yfinance
scipy

Usage
Input the number of stocks and their symbols.
The script fetches historical data, calculates log returns, and optimizes the portfolio.
Outputs include optimal weights, expected annual return, volatility, and the Sharpe Ratio.
