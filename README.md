📈 ## Real-Time Stock Price Dashboard

A full-stack stock market dashboard built with Python, Streamlit, and Plotly, providing real-time price tracking, customizable charts, and technical analysis tools. Monitor multiple tickers, apply indicators like SMA, EMA, and RSI, and view historical trends—all in one interactive app.

Track and analyze stock prices in real time with an intuitive web-based dashboard.

🔧 Features

🔁 Live Stock Data – Real-time updates for selected tickers.

📊 Interactive Charts – Candlestick and line chart options.

📈 Technical Indicators – SMA 20, EMA 20, RSI 14 overlays.

🕰️ Historical Data – Analyze past performance across custom timeframes.

📌 Multi-Ticker Support – View and track multiple stocks at once.

📥 Installation

⚙️ Requirements
Python 3.8+

Recommended libraries:

streamlit

yfinance

pandas

plotly

ta

pytz

🧑‍💻 How to Use

Ticker: Enter a stock symbol (e.g., AAPL)

Time Period: Choose from 1d, 1wk, 1mo, 1y, etc.

Chart Type: Select either Candlestick or Line

Indicators: Add SMA 20, EMA 20, and RSI 14 overlays

Update: Click the Update button to refresh the visualization

Example:

To monitor Apple Inc. (AAPL):

Ticker: AAPL

Time: 1d

Chart: Candlestick

Indicators: SMA 20, EMA 20, RSI 14

For historical analysis:

Select a time period like 1y

Choose Line chart

Analyze data trends and indicator performance

⚠️ Known Issues

Invalid Tickers: If the stock symbol is incorrect or not supported, a data error will be shown.

Network Delays: Real-time updates rely on external APIs, which may experience lag.

🛠️ Customization

To change the default list of stocks being monitored:

Edit the stock_symbols list in app.py.
