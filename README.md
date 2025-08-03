Hi! I'm a finance graduate learning quantitative finance, and this is one of my first practice projects. It implements a Simple Moving Average (SMA) Crossover Strategy using Python. This strategy simulates basic algorithmic trading signals and helps me understand how backtesting and financial data analysis work in quant trading.

1️⃣ Tools & Libraries Used
🐍 Python (core programming)

📦 pandas – for data handling

📉 yfinance – to fetch stock data from Yahoo Finance

📊 matplotlib – for visualizing trades

🔢 numpy – for mathematical operations

2️⃣ Strategy Summary
Buy Signal: When 50-day SMA crosses above 200-day SMA

Sell Signal: When 50-day SMA crosses below 200-day SMA

The strategy only uses closing prices of the stock.

3️⃣ Project Files
File	Description
sma_strategy.py	Core Python script that runs the strategy
strategy_plot.png	Visual output showing Buy/Sell signals (optional)
requirements.txt	Python dependencies needed to run this project

4️⃣ How to Run the Project
Make sure Python is installed. Then follow these steps:

bash
Copy
Edit
# Step 1: Install the required libraries
pip install -r requirements.txt

# Step 2: Run the strategy code
python sma_strategy.py
The output will display:

A graph with price, SMA lines, and Buy/Sell markers

A performance comparison between market returns and strategy returns

5️⃣ What I Learned
How to collect real financial data using APIs

How to compute technical indicators (SMA)

How to build a signal-based trading strategy

How to visualize and interpret trading signals

How to compare a strategy to benchmark performance





