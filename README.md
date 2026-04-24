# Stock Analyzer Project

## About the Project
A web-based stock analysis tool that allows users to visualize price trends and generate simple trading signals using moving averages.

This project focuses on applying basic technical analysis concepts in a clean and interactive interface.

## Key Features
- Real-time stock data using yFinance
- Price visualization with Matplotlib
- Moving averages:
  - 50-day Moving Average (MA50)
  - 20-day Exponential Moving Average (EMA20)
  - 50-day Exponential Moving Average (EMA50)
- Trend identification (bullish / bearish)
- Buy / Sell / Wait signal generation
- Simple and responsive UI using Streamlit

## Core Logic
The trading signal is based on:

- BUY → Price > EMA20 > EMA50  
- SELL → Price < EMA20 < EMA50  
- WAIT → Otherwise  

This provides a basic but effective rule-based trading approach.

## Tech Stack
- Python
- Streamlit
- Pandas
- Matplotlib
- yFinance

## What I Learned
- Implementing financial indicators using Pandas
- Working with real-time stock APIs
- Building interactive web apps using Streamlit
- Translating trading logic into code

## Future Improvements
- Add RSI and MACD indicators
- Support multiple stock comparison
- Improve UI/UX design
- Deploy as a public web app

repo link: https://github.com/abhinavrach/stock-analyzer-project
github link: https://github.com/abhinavrach
