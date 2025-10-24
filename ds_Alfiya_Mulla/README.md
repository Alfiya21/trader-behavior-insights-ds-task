
# Data Science Assignment – Trader Behavior Insights
**Candidate:** your_name_here
**Team:** Web3 Trading – Data Science Division

---

## 📘 Overview
This project analyzes how trading behavior (profitability, risk, leverage, volume) aligns with market sentiment (Fear vs Greed).
It uses two datasets:
1. **Hyperliquid Trader Data** – detailed trade-level metrics (account, leverage, PnL, etc.)
2. **Bitcoin Fear & Greed Index** – daily sentiment classification

---

## 🧠 Objectives
- Explore relationships between trader performance and sentiment.
- Quantify differences in PnL, leverage, and volume under Fear vs Greed.
- Visualize trading risk patterns and profitability distributions.
- Build a ready-to-extend modeling pipeline for predictive analytics.

---

## Folder Structure
ds_yourname/
├── notebook_1.ipynb # Main Colab notebook
├── csv_files/
│ ├── daily_aggregate.csv
│ ├── trades_sample.csv
│ └── merged_trader_sentiment.csv
├── outputs/
│ ├── pnl_distribution.png
│ ├── pnl_by_side.png
│ └── fear_greed_comparison.png
├── ds_report.pdf # Final summarized report
└── README.md # This file

---

## 🛠️ Tools Used
- Python 3.10
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- FPDF (for PDF generation)

---

## 📈 Key Findings
- Leverage and trading volume tend to increase in “Greed” phases.
- Average PnL per trade slightly improves, but win rates remain stable.
- Profit distributions are heavily skewed, with few trades driving gains.
- Sentiment data can potentially enhance trading strategy timing.

---

## Next Steps
- Extend dataset to multiple months for robust temporal modeling.
- Build trader segmentation by risk behavior (clustering).
- Integrate real-time sentiment APIs for live predictive analytics.

---

**Generated:** 2025-10-24 14:55:17 UTC
