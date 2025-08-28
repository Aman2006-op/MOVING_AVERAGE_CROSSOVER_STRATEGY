# MOVING_AVERAGE_CROSSOVER_STRATEGY
Description

This project implements a Simple Moving Average (SMA) Crossover Strategy for stock market trading. The strategy uses two different moving averages—a short-term SMA and a long-term SMA—to generate buy and sell signals.
Buy Signal: When the short-term SMA crosses above the long-term SMA (bullish crossover).
Sell Signal: When the short-term SMA crosses below the long-term SMA (bearish crossover).
This is one of the most popular technical analysis strategies, often used by traders to capture market trends.

Features

Fetches historical stock data using yfinance.
Calculates short-term and long-term SMAs.
Generates buy and sell signals based on crossovers.
Visualizes stock price with moving averages and signals using matplotlib.
Allows users to test strategy performance on different stocks and timeframes.

Tools & Libraries

Python
yfinance → For downloading historical market data.
pandas → For data manipulation.
matplotlib → For plotting price charts with crossover signals.

Practical Use

This project serves as an introductory trading strategy model. While simple, it demonstrates how technical indicators can be applied to real-world financial data. 
It can be extended into:
Backtesting frameworks.
Risk management features (like stop-loss).
Integration with other indicators (RSI, MACD, etc.)
