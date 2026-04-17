# Geopolitical Risk and Financial Market Volatility 2025-2026

## Overview
This project analyses how major geopolitical events in 2025-2026 impacted 
oil prices, currency markets and equity indices. Using Python and real 
market data, I quantify the shock impact of six key events including the 
US/Israel strikes on Iran, Trump tariff announcements and the Iran ceasefire.

## Key Findings
- The March 2026 US/Israel strikes on Iran caused a **28.9% oil price surge** 
  in under two weeks, the largest single geopolitical shock in the dataset
- Trump tariff announcements triggered **simultaneous selloffs** across oil 
  (-12.6%), FTSE (-10.8%) and S&P 500 (-3.8%), a systemic shock vs the 
  Iran conflict which was an isolated energy shock
- A UK business importing $1,000,000 of goods faced **£121,338 in additional 
  fuel costs** following the Iran strikes
- A £10,000,000 FTSE portfolio lost **£428,938 in 14 days** following the strikes
- Oil volatility reached **100% annualised** during the Iran conflict, four 
  times the normal levels
- Despite oil volatility, GBP/USD remained the most stable asset with only 
  **2.8% coefficient of variation** throughout the period

## Methodology
- **Data Source:** Yahoo Finance via yfinance API
- **Assets Analysed:** Brent Crude Oil, GBP/USD, FTSE 100, S&P 500
- **Time Period:** January 2025 to April 2026 (332 trading days)
- **Techniques Used:**
  - Descriptive statistics with kurtosis and skewness analysis
  - 30-day rolling volatility (annualised)
  - Correlation matrix of daily returns
  - Event study analysis (5-day pre and post event returns)
  - Real world business and investor impact quantification

## Tools and Technologies
- Python 3.13
- pandas, numpy, matplotlib, seaborn, yfinance
- Jupyter Notebook

## Key Insight
Two distinct types of geopolitical shock emerged from this analysis. 
Trade and tariff shocks created correlated selloffs across all asset 
classes simultaneously, systemic risk. Military conflict shocks 
concentrated in energy markets with limited spillover into equities, isolated supply risk. For portfolio managers and risk analysts, 
the hedging strategy for each shock type is fundamentally different.

## Files
- `geopolitical_risk_financial_markets.ipynb` — Full analysis notebook
- `geopolitical_market_volatility.png` — Normalised price chart
- `rolling_volatility.png` — 30-day rolling volatility chart
- `correlation_matrix.png` — Asset correlation heatmap
- `event_study.png` — Event study shock impact chart

## Author
Thivaan Mathyalahan — Economics Graduate | Data Analyst
[LinkedIn](https://www.linkedin.com/in/thivaanmathy)
