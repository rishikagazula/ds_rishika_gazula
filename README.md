# Trader Behavior vs Market Sentiment

This project analyzes how trader behavior changes under different market sentiment conditions (Fear vs Greed) in the cryptocurrency market. The analysis is based on historical trader data and the Bitcoin Fear & Greed Index.


Objective

The main objective of this assignment is to understand:
- How trader profitability varies during Fear and Greed market phases
- How risk-taking behavior changes based on market sentiment


Datasets Used

1. **Bitcoin Fear & Greed Index**
   - Columns: Date, Classification (Fear / Greed)
   - Represents overall market sentiment

2. **Historical Trader Data (Hyperliquid)**
   - Trade-level data including trade size, execution price, trade time, and closed profit/loss (closedPnL)


Methodology

- Converted trade timestamps into date format
- Standardized date format in both datasets
- Merged trader data with market sentiment data using the date column
- Performed exploratory data analysis (EDA)
- Compared trader behavior during Fear and Greed periods

> Note: Since leverage data was not available in the trader dataset, trade size and PnL volatility were used as proxy indicators to analyze risk-taking behavior.


Key Analyses Performed

- Average profit/loss comparison between Fear and Greed
- Trade size (volume) comparison as a risk proxy
- PnL volatility analysis
- Win rate comparison
- Loss severity analysis


Key Insights

- Traders tend to place larger trades during Greed phases
- Risk-taking behavior increases when market sentiment is Greed
- Loss severity is higher during Fear periods
- Market sentiment affects risk behavior more than win rate


Tools & Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab


Project Structure

- `notebook_1.ipynb` – Main analysis notebook
- `csv_files/` – Processed datasets
- `outputs/` – Charts and visualizations
- `ds_report.pdf` – Final summarized analysis report
- `README.md` – Project overview and instructions


Google Colab Link:
https://colab.research.google.com/drive/19U0Vd4tMMnwjLPdL06M75Xv22YdbDYaK?usp=sharing

Conclusion

This project highlights the strong relationship between market sentiment and trader behavior. Understanding sentiment-driven behavior can help design better risk management and trading strategies in crypto markets.

