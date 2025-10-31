# Trader Performance Analysis by Market Sentiment

## Project Overview
This project analyzes the relationship between **market sentiment** (Fear, Greed, Extreme Fear, Extreme Greed, Neutral) and **trader performance** using historical trading data from the Hyperliquid platform.  
By integrating sentiment data with real trading metrics, the study identifies how the emotional states of the market influence profitability and trading behavior.

---

## Datasets Used

### 1. Bitcoin Market Sentiment Dataset
- **Columns:** Date, Classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)
- **Purpose:** Represents daily overall market emotions.

### 2. Hyperliquid Trader Dataset
- **Columns:** account, symbol, execution price, size, side, time, start position, event, closedPnL, leverage, and related trade metrics.
- **Purpose:** Contains detailed historical trader activity and profit/loss data.

---

## Summary of Results

| Market Sentiment | Avg Closed PnL | Total Closed PnL | Total Trades |
|------------------|----------------|------------------|--------------|
| Extreme Greed    | 67.89          | 2,715,171.31     | 39,992       |
| Fear             | 54.29          | 3,357,155.44     | 61,837       |
| Greed            | 42.74          | 2,150,129.27     | 50,303       |
| Extreme Fear     | 34.54          | 739,110.25       | 21,400       |
| Neutral          | 34.31          | 1,292,920.68     | 37,686       |

---

## Key Insights

- Trader performance is highest during **Extreme Greed** phases, showing superior profit efficiency per trade.  
- **Fear sentiment** results in the highest total profit and trading volume, reflecting increased market participation during volatility.  
- **Neutral** and **Extreme Fear** conditions lead to fewer trades and lower profitability.  
- The results indicate that traders tend to take more profitable risks during optimistic conditions and trade conservatively during fear phases.

---

## Methodology

1. **Data Preprocessing:** Cleaned and merged sentiment and trading datasets using Python (Pandas).  
2. **Computation:** Calculated average and total closed PnL grouped by sentiment category.  
3. **Visualization:** Generated sentiment-based performance plots using Matplotlib and Seaborn.  
4. **Export:** Saved results as CSV and generated a structured report in PDF format.

---

## Files Generated

- `sentiment_performance_summary.csv` – Summary of trader performance metrics.  
- `performance_summary_plot.png` – Visualization of sentiment-wise performance.  
- `ds_report.pdf` – Final detailed report containing all insights and interpretations.

---

## Technologies Used

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Google Colab  

---

## Folder Structure

```
ds_Pavithra/
├── notebook_1.ipynb
├── csv_files/
│   └── sentiment_performance_summary.csv
├── outputs/
│   ├── performance_summary_plot.png
│   ├── market_sentiment_analysis.png
│   └── top10_trader_performance.png
├── ds_report.pdf
└── README.md
```

---

## Google Colab Notebook Link

[View Google Colab Notebook](https://colab.research.google.com/drive/180EoZ5h6y9KHqo4Wrgk72GWds9_eb8Hm?usp=sharing)

---

## Prepared By

**Name:** Pavithra  
**Date:** 31 October 2025
