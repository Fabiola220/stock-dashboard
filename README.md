# Real-Time Stock Price Dashboard

The Real-Time Stock Price Dashboard is a full-stack financial analytics web app built with Python, Streamlit, and Plotly to track and analyze stock market data in real time.
It features live price updates, customizable technical indicators, and historical trend analysis — all within an interactive, browser-based interface.

This project was developed to practice data-driven web application development and demonstrate API integration, real-time data handling, and financial data visualization.

## 🔧 Features

**🔁 Live Stock Data** – Real-time updates for selected tickers.
**📊 Interactive Charts** – Candlestick and line chart options.
**📈 Technical Indicators** – SMA 20, EMA 20, RSI 14 overlays.
**🕰️ Historical Data** – Analyze past performance across custom timeframes.
**📌 Multi-Ticker Support** – View and track multiple stocks at once.

## 🛠️ Tech Stack
- **Frontend & UI**: Streamlit
- **Data & APIs**: yfinance (Yahoo Finance)
- **Charting**: Plotly
- **Data Analysis**: pandas, ta (technical analysis library)
- **Utilities**: pytz (timezone handling)

## 📥 Installation

**⚙️ Requirements**
- Python 3.8+
- Recommended libraries:
**streamlit**
**yfinance**
**pandas**
**plotly**
**ta**
**pytz**

## 🧑‍💻 How to Use

- Ticker: Enter a stock symbol (e.g., AAPL)
- Time Period: Choose from 1d, 1wk, 1mo, 1y, etc.
- Chart Type: Select either Candlestick or Line
- Indicators: Add SMA 20, EMA 20, and RSI 14 overlays
- Update: Click the Update button to refresh the visualization

## Example:

  **To monitor Apple Inc. (AAPL):**
Ticker: AAPL
Time: 1d
Chart: Candlestick
Indicators: SMA 20, EMA 20, RSI 14
For historical analysis:
Select a time period like 1y
Choose Line chart
Analyze data trends and indicator performance

## System Architecture Explanation

1. User Browser / Streamlit UI – The user selects a stock ticker, date range, and indicators.
2. Streamlit Backend (Python) – Handles requests and calls the financial API for live data.
3. Financial Data API – Provides real-time market data in JSON format.
4. Plotly Chart Generator – Processes data, calculates indicators, and creates interactive charts.
5. UI Updates – The charts are displayed on the dashboard instantly.

## ⚠️ Known Issues

- Invalid Tickers: If the stock symbol is incorrect or not supported, a data error will be shown.
- Network Delays: Real-time updates rely on external APIs, which may experience lag.

## 🛠️ Customization

To change the default list of stocks being monitored:
Edit the stock_symbols list in app.py.

 ## Why I Built This
I created this project to:

- Enhance my skills in real-time data fetching, processing, and visualization.
- Gain hands-on experience with financial market APIs and technical analysis.
- Build a practical tool that can be adapted for professional finance workflows.
- Showcase full-stack Python development capabilities.
