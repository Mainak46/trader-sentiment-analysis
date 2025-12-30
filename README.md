# Trader Behavior Insights – Fear vs Greed Analysis

## 📌 Objective
Analyze how market sentiment (Fear and Greed) impacts trader behavior and performance using historical trading data.

## 📊 Datasets Used
- Bitcoin Fear & Greed Index
- Hyperliquid Historical Trader Data

## 🔧 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## 🧹 Data Preparation
- Converted Excel serial timestamps to datetime
- Created trade-level date column
- Merged trader data with market sentiment data
- Removed irrelevant technical columns

## 📈 Analysis Performed
- Profit/Loss comparison across market sentiment
- Win-rate analysis (Fear vs Greed)
- Trade volume and exposure analysis
- Buy vs Sell behavior study
- PnL volatility analysis

## 🔍 Key Insights
- Traders increase position size during Greed, increasing exposure.
- Fear periods show higher PnL volatility and risk.
- Buy trades dominate Greed sentiment; Sell trades increase during Fear.
- A small group of traders consistently outperforms across sentiments.
