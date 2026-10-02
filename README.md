# 📈 Stock Moving Average Analysis & Crossover Signals

A Python-based financial data analysis tool that calculates and visualizes **Simple Moving Averages (SMA)** and **Exponential Moving Averages (EMA)** for historical stock market data. This project helps identify market trends, golden/death cross signals, and potential entry/exit points for trading strategies.

---

## 🌟 Features

- **Automated Data Retrieval**: Fetches real-time and historical stock data using `yfinance`.
- **Moving Average Indicators**:
  - **SMA (Simple Moving Average)**: Calculates unweighted averages across customizable short-term and long-term windows (e.g., 20-day, 50-day, 200-day).
  - **EMA (Exponential Moving Average)**: Applies exponential weighting to place higher importance on recent price action.
- **Crossover Signal Detection**:
  - 🟢 **Golden Cross**: Short-term MA crosses above long-term MA (Bullish signal).
  - 🔴 **Death Cross**: Short-term MA crosses below long-term MA (Bearish signal).
- **Visual Analytics**: Dynamic plots using `matplotlib` / `seaborn` displaying stock price trends alongside moving average overlays.

---

## 🛠️ Tech Stack & Requirements

- **Language**: Python 3.8+
- **Libraries Used**:
  - `pandas` - Data manipulation & rolling window computations
  - `numpy` - Numerical operations
  - `yfinance` - Stock historical price extraction
  - `matplotlib` & `seaborn` - Financial charts and trend visualizations

---
