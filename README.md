# Trader Behavior vs Market Sentiment Analysis

## Objective
This project analyzes how Bitcoin market sentiment (Fear/Greed Index) influences trader behavior and performance on the Hyperliquid platform.

The goal is to identify behavioral patterns that can support more informed trading strategies.

---

## Datasets
1. Bitcoin Fear/Greed Index  
2. Hyperliquid Historical Trader Data  

Both datasets were aligned at a daily level using timestamps.

---

## Methodology
- Data cleaning and normalization of column names
- Timestamp parsing and date alignment
- Feature engineering (daily PnL, win rate, trade frequency, average size)
- Merging sentiment and trading data
- Exploratory data analysis and visualization
- Trader segmentation
- Baseline predictive modeling using Logistic Regression

---

## Key Insights
- Position sizes tend to increase during Fear and Neutral periods.
- Average profitability is higher during Greed phases, but with increased volatility.
- High-frequency and consistently profitable traders perform better during positive sentiment periods.

---

## Strategy Recommendations
1. During Fear periods, traders should reduce position sizes to limit downside risk.
2. Aggressive trading strategies should be applied selectively during Greed phases for historically profitable accounts.

---

## Repository Structure
- Notebook: Main analysis
- outputs/: Charts and summary tables

---

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook hyperliquid_trader_behavior_vs_sentiment.ipynb
