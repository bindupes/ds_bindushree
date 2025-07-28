Trader Performance vs Market Sentiment Analysis

Overview

This data science project analyzes how **trading behavior** (profitability, risk, volume, and leverage) aligns or diverges from the **Bitcoin Fear-Greed Index** sentiment. The goal is to identify key trends, performance metrics, and trading strategies that perform well under different sentiment conditions (e.g., Fear, Greed, Extreme Fear).

---
Objective

- Analyze trading patterns and sentiment dynamics.
- Measure trader profitability under different sentiment regimes.
- Identify top traders who perform well in specific sentiment types.
- Reveal correlations between market sentiment and risk-taking behavior.

---

Project Structure
ds_bindushree/
├── final.ipynb # Main analysis notebook (Google Colab)
├── csv_files/ # Cleaned & intermediate data
│ ├── merged_sentiment_trading_data.csv ( file above 25MB , no uploaded in github)
│ ├── pnl_by_sentiment.csv
│ ├── top_traders.csv
│ ├── trader_scores.csv
│ ├── classification_counts.csv
│ └── heatmap_data.csv
├── output/ # Plots and visual outputs
│ ├── sentiment_distribution.png
│ ├── avg_pnl_by_sentiment.png
│ ├── win_rate_sentiment.png
│ ├── pnl_boxplot.png
│ ├── correlation_heatmap.png
│ └── top_traders_table.png
├── report.pdf # Final PDF report (insights & results)
└── README.md # Project documentation (this file)


---

Tools & Libraries

- Python 3 (Google Colab)
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (MinMaxScaler)
- Statistics & EDA

---

Key Tasks Performed

- Merged sentiment data with historical trading data by date.
- Cleaned and preprocessed over 200,000 trading records.
- Created new features like **profitability flag**, **ROI**, and **trader scores**.
- Performed exploratory data analysis (EDA) on:
  - Sentiment distribution
  - Average PnL by sentiment
  - Profitability (Win Rate)
  - Boxplots & correlation heatmaps
- Ranked top traders using a composite score of PnL and Win Rate.

---

Insights & Findings

- **Extreme Greed** is the most profitable sentiment class on average.
- **Fear** also shows strong profitability, contrary to expectations.
- Traders incur **higher risk and volatility** in sentiment extremes.
- A few traders show consistent performance even in **Extreme Fear**, indicating potential **contrarian strength**.
- Higher position sizes lead to higher fees, but not necessarily higher profitability.
- Trader behavior significantly varies with market sentiment.

---

 Submission Notes

- All files are organized as per the given directory format.
- Intermediate CSVs and final outputs are stored separately.
- Final PDF report captures actionable insights.

---

