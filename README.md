# stock-analyzer-project
A web-based stock analysis tool with moving averages and buy/sell signals

# Stock Analyzer Project

## Overview
This project is a web-based stock analysis tool that helps users analyze stocks using price trends and moving averages.

## Features
- Enter stock ticker to fetch real-time data
- Plot stock price graph
- 50-day Moving Average (MA50)
- 20-day Exponential Moving Average (EMA20)
- 50-day Exponential Moving Average (EMA50)
- Trend analysis (uptrend / downtrend)
- Buy / Sell / Wait signal generation
- Clean and simple UI using Streamlit

## How It Works
The tool uses historical stock data and applies technical indicators:

- **Price vs Moving Averages**
- **EMA20 vs EMA50 crossover**
- **Trend direction**

### Signal Logic
- BUY → Price > EMA20 > EMA50  
- SELL → Price < EMA20 < EMA50  
- WAIT → Otherwise  

## Tech Stack
- Python
- Streamlit
- yFinance
- Pandas
- Matplotlib

repo link: https://github.com/abhinavrach/stock-analyzer-project
github link: https://github.com/abhinavrach
