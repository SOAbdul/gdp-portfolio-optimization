# gdp-portfolio-optimization: GDP and Financial Market Analysis

This repository analyzes the relationship between **macroeconomic indicators (GDP)** and **financial market performance (S&P 500, AGG, ETFs)**. It also includes portfolio optimization and evaluation techniques using modern finance libraries.


##  Features

- **Data Collection**
  - GDP data from FRED (`pandas_datareader`)
  - Market data (S&P 500, AGG, ETFs) from Yahoo Finance and `yahooquery`
  - ETF list from `etfpy`

- **Data Transformation**
  - Convert daily data to monthly frequency
  - Align GDP and market datasets
  - Compute correlations between GDP and market indices

- **Economic Cycle Detection**
  - Compute GDP growth rates
  - Identify **growth periods** and **recession periods**
  - Extract recession start & end dates with durations

- **Portfolio Optimization**
  - Mean-variance optimization using `cvxpy`
  - Constraints: weights, diversification, budget constraints
  - Risk-return trade-off analysis

- **Performance Metrics**
  - Sharpe Ratio
  - Treynor Ratio
  - Alpha & Beta against benchmarks

- **Visualization**
  - GDP vs S&P 500/AGG plots
  - Recession vs growth highlighting
  - Portfolio return distribution plots



## Project Structure

- `macro_portfolio_optimization.ipynb` → Main notebook with full analysis
- `requirements.txt` → Python dependencies (to be added)

