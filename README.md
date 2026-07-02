# 📈 Stock Market Performance & Volatility Analysis

Analysis of 5 years (2013–2018) of daily stock price data for six major companies — Apple, Amazon, Microsoft, Google, Netflix, and JPMorgan — using SQL and Python to explore growth, volatility, and the risk-return relationship between them.

## 🔑 Key Findings

- **Netflix delivered the highest growth (923%) and the highest volatility (2.74% average daily swing)** of the six stocks analyzed, while **JPMorgan showed the most stable price behavior (1.28% volatility) but the lowest growth (132%)** — consistent with the classic risk-return tradeoff seen across financial markets.
- Despite having a lower share price than Amazon or Google, **Apple had by far the highest trading volume (~54M shares/day)** — a reflection of shares outstanding rather than company value.
- Raw price-based comparisons can be misleading: Amazon and Google had the highest absolute closing prices, but Netflix outpaced both in percentage growth by starting from a much lower base.

## 🛠️ Tools & Skills Used

- **SQL** (SQLite / DB Browser) — data querying, joins, subqueries, aggregate analysis
- **Python** (pandas) — data cleaning, daily return calculation, rolling averages, volatility (standard deviation)
- **Power BI** — interactive dashboard *(in progress)*
- Git & GitHub for version control

## 📊 Dataset

[S&P 500 stock data (Kaggle)](https://www.kaggle.com/datasets/camnugent/sandp500) — daily OHLCV price data, 2013–2018, for all S&P 500 companies. This analysis focuses on a subset of 6 tickers: AAPL, AMZN, MSFT, GOOGL, NFLX, JPM.

*(Raw data files are not included in this repo — download from the Kaggle link above to reproduce.)*

## 📁 Project Structure

- `stock_analysis.ipynb` — main analysis notebook: data loading, cleaning, daily returns, volatility, moving averages
- `sql_queries.sql` — SQL exploration queries *(add this if you want to save your SQL work too)*
- Power BI dashboard — *(coming soon)*

## 🚀 About This Project

This is a self-directed learning project built while transitioning into data analytics after graduating with a BS in Computer Science. It's part of an ongoing portfolio documenting my progress from SQL/Python fundamentals through to dashboard-building.

## 📌 Status

🟢 Active — currently building out the Power BI dashboard as the next step.

---
*Built as part of a self-directed data analytics learning path.*
