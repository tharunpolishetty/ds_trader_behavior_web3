# 📊 Trader Behavior vs Market Sentiment – Data Science Assignment

This project explores how trader performance and behavior change across different market
sentiment regimes using:

- **Hyperliquid Historical Trading Data**
- **Crypto Fear & Greed Index**

The goal is to uncover how **profitability, volume, and long/short bias** differ during market
conditions such as Extreme Fear, Fear, Neutral, Greed, and Extreme Greed.


## 🛠️ Tech Stack
| Category | Tools & Libraries |
|-----------|------------------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Development | Google colab |




---

## 🚀 How to Use This Project

1. Open **`notebook_1.ipynb`** in Google Colab.  
2. Upload the raw datasets:
   - `historical_data.csv`
   - `fear_greed_index.csv`
3. Run all cells from top to bottom.
4. Outputs will be automatically saved to:
   - `csv_files/`  
   - `outputs/`

---

## 🔍 Key Analysis Steps

- Cleaned and standardized timestamps  
- Merged trades with daily market sentiment  
- Engineered features:
  - Profitability flag  
  - Long/short encoding  
  - Daily aggregates (PnL, volume, win rate, bias)
- Generated Seaborn visualizations
- Summarized findings in **ds_report.pdf**

---

## 📈 Key Insights

- **Win rate is highest during Extreme Greed**, indicating strong trend-following opportunities.  
- **Trading volume spikes during Extreme Fear**, showing high activity in volatile markets.  
- **Extreme Fear and Extreme Greed provide the best PnL environments**.  
- Traders show a **short bias during Extreme Greed**, likely hedging overbought conditions.  

Full details available in **ds_report.pdf**.

---

## 🔗 Colab Notebook (View Only)

👉 Add your shareable Colab link here:

