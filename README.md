# Yahoo-Finance-Stock-Dashboard

## 📊 Project Overview

The **Stock Tracker** is a dynamic web dashboard built using **Dash** and **Plotly**. This application allows users to input a stock ticker (e.g., AAPL) and visualize two key charts:

1. **Candlestick Chart:** Displays the historical stock price movements with moving averages for a specified period.
2. **Volume Bar Chart:** Shows the trading volume of the stock over time.

Users can specify the number of days (from 1 to 5) for which the stock data will be fetched, and the dashboard will update the visualizations accordingly.

### Data Source:
The data is fetched using **yfinance** (Yahoo Finance) API, which provides stock market data, including stock prices and trading volumes.

## 💻 Technologies Used

- **Python:** The primary language used to develop the dashboard.
- **Dash:** A Python framework for building web applications with interactive visualizations.
- **Plotly:** Used for creating interactive visualizations like candlestick and bar charts.
- **yfinance:** Used to fetch real-time stock market data.
- **Pandas:** For data manipulation and processing.

## 📂 Getting Started

### Prerequisites:
Before running the code, make sure you have Python and the necessary libraries installed.

1. **Install Python**: Download Python from [python.org](https://www.python.org/downloads/).

2. **Install required libraries**: Run the following command to install the necessary libraries:

```bash
pip install dash pandas plotly yfinance

