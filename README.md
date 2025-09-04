# Power BI – Comparative Analysis of Stock Market Data (IVV vs Microsoft)

## Project Overview
This project was developed as part of a bachelor’s thesis and focuses on the use of **Power BI** in stock market data analysis. The main goal was to compare investments in the **iShares Core S&P 500 ETF (IVV)**, which replicates the S&P 500 index, with a single company – **Microsoft Corporation (MSFT)**.

The analysis was based on data retrieved from **API Profit.com** and included both **fundamental** and **technical analysis**, as well as key risk indicators. 

---

## Project Structure
The project consists of **three Power BI dashbards**:

### ETF Dashboard - iShares Core S&P 500 (IVV)
- Key fund statistics (Company, Category, Holdings, Net Expense Ratio, Dividend Yield, Total Net Assets, Market Cap).  
- ROI over different horizons: 1y, 3y, 5y, 10y.  
- Annualized Volatility (1y, 2y, 3y).  
- Line chart of closing prices (with range selection: 1m, 3m, 6m, 2y, 5y).  
- Candlestick chart (8w, 4w, 12w).  
- Top holdings breakdown by percentage.
<img width="920" height="487" alt="image" src="https://github.com/user-attachments/assets/733017df-7d25-4286-83d6-a47e82cedd68" />

### Company Dashboard -Microsoft (MSFT)
- Key fundamental data (P/E ratio, Dividend Yield, Dividend per Share, Total Assets, sector, industry).  
- ROI over different horizons: 1y, 3y, 5y, 10y.  
- Annualized Volatility (2020–2024).  
- Technical indicators:
  - **SMA (Simple Moving Average)**.  
  - **Bollinger Bands**.
  - **MACD (Moving Average Convergence Divergence)**. 
  - **RSI (Relative Strength Index)**.  
  - **MDD (Max Drawdown)**.
<img width="1005" height="704" alt="image" src="https://github.com/user-attachments/assets/a1ac46f0-0e6a-4188-a168-4eee97f549d2" />

### Comparison Dashboard – IVV vs Microsoft
- ROI (2020–2024 and different horizons).  
- Annualized Volatility (2020–2024 and different horizons).  
- MDD (2020–2024).  
- Beta (2020–2024).  
- Correlation (2020–2024).
<img width="1006" height="528" alt="image" src="https://github.com/user-attachments/assets/592377cc-ec3f-4bcf-82a8-c6f770248269" />

## Key Findings 
- Microsoft delivered **higher long-term returns** (e.g. ROI 10y = 956.75% vs IVV = 231.35%) but with significantly **higher risk** (volatility, MDD, beta).  
- ETF IVV proved to be **more stable and diversified**, with lower volatility and smaller drawdowns (e.g. MDD in 2022: MSFT = -35%, IVV = -24%).  
- The correlation between MSFT and IVV was high (0.6–0.9), showing similar market direction but different levels of sensitivity to risk.  
- Power BI turned out to be an effective tool for **data integration, visualization, and financial analysis**.

## Technologies
- **Power BI**.
- **DAX (Data Analysis Expressions)**.
- **R**.
- **API Profit.com** – data source.  
