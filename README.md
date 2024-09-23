# Stock Market Analysis and Trading Strategy Development

## Introduction
This project analyzes historical stock data from the Nifty 50 index, develops a trading strategy using moving averages, and incorporates risk management techniques.

## Table of Contents
- [Task 1: Stock Data Analysis](#task-1-stock-data-analysis)
- [Task 2: Strategy Development](#task-2-strategy-development)
- [Task 3: Risk Management](#task-3-risk-management)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Task 1: Stock Data Analysis
1. **Fetched Historical Data**: 
   - Used the `yfinance` library to obtain stock prices for 5 companies over the last 6 months.
   
2. **Daily Percentage Change**: 
   - Calculated the daily percentage change for each stock.
   
3. **Plots**: 
   - Visualized closing prices and daily percentage changes.
   - Calculated and plotted a 20-day moving average to understand stock trends.

## Task 2: Strategy Development
1. **Moving Average Crossover Strategy**:
   - Developed a trading strategy using a 50-day short-term and 200-day long-term moving average.
   
2. **Buy/Sell Signals**:
   - Generated buy signals when the short-term average crossed above the long-term average, and sell signals when it crossed below.
   
3. **Backtesting**:
   - Compared the performance of this strategy against a buy-and-hold approach by calculating cumulative returns.

## Task 3: Risk Management
1. **Maximum Drawdown**:
   - Calculated the maximum drawdown for each stock to assess risk.
   
2. **Stop-Loss Mechanism**:
   - Implemented a 5% stop-loss for the selected stock and compared performance with the original strategy.

## Visualizations
- **Closing Prices and Moving Averages**:
![Closing Prices](path/to/closing_prices_plot.png)

- **Daily Percentage Change**:
![Daily Percentage Change](path/to/daily_percentage_change_plot.png)

- **Cumulative Returns Comparison**:
![Cumulative Returns](path/to/cumulative_returns_plot.png)

## Conclusion
This project demonstrates a comprehensive approach to stock market analysis, combining data analysis, trading strategy development, and risk management. The results provide insights into the effectiveness of moving average strategies and the importance of risk assessment in trading.

## Requirements
- Python 3.x
- Libraries: `yfinance`, `pandas`, `matplotlib`, `numpy`

## Installation
```bash
pip install yfinance pandas matplotlib numpy
