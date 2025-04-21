# 📊 Portfolio Performance Analysis (5-Year)

A data-driven mini project for analyzing the performance of a personal investment portfolio over 5 years, comparing it with major U.S. market indices (NASDAQ, S&P 500, and Dow Jones).  
This project is built using Python in Google Colab with real financial datasets, leveraging core data analysis and visualization tools.

The dataset used in this project is sourced from Kaggle. It contains detailed information about stock portfolios and market indices, which is essential for portfolio analysis and performance tracking.

You can access the dataset here:

[🌐 Kaggle Dataset: Stock Portfolio Data with Prices and Indices](https://www.kaggle.com/datasets/nikitamanaenkov/stock-portfolio-data-with-prices-and-indices/data)


## 🔍 Project Objectives

- Analyze historical performance of a personalized stock portfolio
- Compare portfolio returns with market indices (NASDAQ, S&P 500, Dow Jones)
- Evaluate key metrics such as cumulative return, volatility, and Sharpe Ratio
- Visualize sector allocation, performance trends, and relative benchmarks
- Demonstrate real-world data analysis skills using Python and pandas

---

## 📁 Dataset Overview

| File | Description |
|------|-------------|
| `data/portfolio.csv` | Holdings overview: ticker, quantity, sector, closing price, weight |
| `data/portfolio_prices.csv` | Historical prices and daily returns of stocks in the portfolio |
| `data/nasdaq.csv` | Historical performance of the NASDAQ Composite index |
| `data/sp500.csv` | Historical performance of the S&P 500 index |
| `data/dowjones.csv` | Historical performance of the Dow Jones index |

All datasets are structured and enriched with data pulled from **Yahoo Finance**.

---

## 🛠️ Tools & Libraries

- Python 3
- Google Colab
- `pandas`, `numpy` – data processing
- `matplotlib`, `seaborn` – visualization
- `scipy` / `statsmodels` (optional for advanced stats)

---

## 📊 Key Visualizations

- Sector allocation pie chart
- Cumulative returns comparison (Portfolio vs. Indices)
- Volatility & risk metrics
- Portfolio weight analysis
- Correlation heatmap (optional)

---

## 📊 Sample Metrics

The project provides a comprehensive analysis of portfolio performance. Below are some sample metrics calculated based on the data:

### 1. **Cumulative Return**:
   - **Portfolio Cumulative Return**: This metric represents the total return on the portfolio over the specified period. For example, if the portfolio started with $10,000 and increased to $12,000 after 5 years, the cumulative return would be 20%.
   - **Sample Value**: 15.2%

### 2. **Volatility**:
   - **Portfolio Volatility**: This metric measures the fluctuation in the portfolio's returns over time, representing the level of risk involved in the investment. A higher volatility indicates a higher level of risk.
   - **Sample Value**: 12.4%

### 3. **Sharpe Ratio**:
   - **Sharpe Ratio**: This metric measures the risk-adjusted return of the portfolio. It compares the excess return (portfolio return minus risk-free rate) to the standard deviation of returns. A higher Sharpe Ratio indicates better risk-adjusted performance.
   - **Sample Value**: 1.82

### 4. **Comparison with Market Indices**:
   - **NASDAQ Composite**: The portfolio’s performance is compared against major market indices such as NASDAQ, S&P 500, and Dow Jones Industrial Average.
   - **Sample Comparison**: Portfolio Return = 15.2%, NASDAQ Return = 10.5%, S&P 500 Return = 12.3%, Dow Jones Return = 11.7%

### 5. **Sector Allocation**:
   - **Portfolio Sector Breakdown**: This metric shows how the portfolio is diversified across various sectors like technology, healthcare, finance, etc.
   - **Sample Allocation**:
     - **Technology**: 40%
     - **Healthcare**: 25%
     - **Finance**: 15%
     - **Consumer Goods**: 10%
     - **Other**: 10%

### 6. **Maximum Drawdown**:
   - **Maximum Drawdown**: This metric calculates the largest peak-to-trough decline in the portfolio value over the analysis period, reflecting the largest potential loss an investor might have experienced.
   - **Sample Value**: 8.3%

### 7. **Return vs Risk**:
   - **Risk-Return Profile**: This metric shows the portfolio's return relative to its risk (volatility). The higher the return relative to risk, the better the portfolio's performance.
   - **Sample Value**: Portfolio Return / Portfolio Volatility = 1.22 (indicating that the return is 1.22 times the volatility)

These metrics are calculated to provide insights into the portfolio's overall performance, volatility, and how it compares to major indices in the market. By analyzing these metrics, investors can make informed decisions about adjusting their portfolio for better returns or reducing risk.


