# Financial Time-Series Analysis in Python

## Project Overview

This project applies Python-based financial time-series analysis to evaluate the performance, volatility, drawdown risk, correlation structure, and trading behaviour of major global equities between 2010 and 2026.

The analysis focuses on combining financial programming, statistical analysis, and investment risk metrics to produce decision-ready insights.

## Objectives

- Analyse historical equity price data
- Calculate annual mean return and annual volatility
- Measure maximum drawdown risk
- Calculate Sharpe ratios for risk-adjusted performance
- Analyse correlation between selected equities
- Apply log transformation and normalisation for better comparison
- Explore moving average-based trading signals
- Present financial insights using Python visualisations

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Statisticals
- Tabulate
- Yahoo Finance data
- Jupyter Notebook

## Dataset

The project analyses 10 global equities:

- AAPL
- AMAT
- AMZN
- CTSH
- CVX
- LRCX
- MSFT
- NVDA
- SHEL
- XOM

The analysis covers price data from 2010 to 2026.

---

## 1. Stock Price Trend Analysis

The first stage of the analysis visualises historical stock price movements across the selected equities.

<img width="1246" height="632" alt="Screenshot 2026-03-05 114001" src="https://github.com/user-attachments/assets/4efc423c-b195-4de9-a471-07a08ffcfb4a" />


This allows comparison of long-term price growth and market behaviour across technology, semiconductor, and energy-related equities.

---

## 2. Risk and Return Summary

The project calculates annualised volatility and annual mean return for each equity.

<img width="733" height="428" alt="Screenshot 2026-02-26 120511" src="https://github.com/user-attachments/assets/8176e242-a055-4394-9ef0-248f7f6f037f" />
<img width="705" height="457" alt="Screenshot 2026-02-26 120516" src="https://github.com/user-attachments/assets/3ababf28-65b9-40be-93d1-0e6c09ce44ba" />



This helps compare each stock’s return potential against its level of volatility.

---

## 3. Maximum Drawdown Analysis

Maximum drawdown measures the largest peak-to-trough decline in price over the analysis period.

<img width="1348" height="537" alt="Screenshot 2026-02-26 125430" src="https://github.com/user-attachments/assets/c9751431-4996-4d8a-bcbf-995a1203f545" />


This is useful for understanding downside risk and how severely each stock declined during market stress periods.

---

## 4. Sharpe Ratio Analysis

The Sharpe ratio is used to compare risk-adjusted returns across the selected equities.

<img width="1279" height="630" alt="Screenshot 2026-02-26 125438" src="https://github.com/user-attachments/assets/b1c1f710-909e-4ece-9aea-5a25eb2e9b84" />


A higher Sharpe ratio suggests stronger return performance relative to volatility.

---

## 5. Descriptive Return Statistics

The project compares average daily returns, volatility, median return, and maximum return across equities.

<img width="1576" height="664" alt="Screenshot 2026-02-26 122726" src="https://github.com/user-attachments/assets/4acfd07f-5915-4252-b6ff-7f58095fad95" />


This provides a broader statistical view of performance and return distribution.

---

## 6. Correlation Analysis

The correlation matrix is used to understand how strongly the selected equities move together.

<img width="1193" height="466" alt="Screenshot 2026-02-26 125530" src="https://github.com/user-attachments/assets/c1c36cd2-2c1c-4d50-98c4-7f224acf364d" />
<img width="4314" height="1866" alt="correlation_heatmap" src="https://github.com/user-attachments/assets/ed85a1df-9f06-425a-99fe-66ca1934bd7b" />



Correlation analysis is useful for portfolio diversification because highly correlated assets may provide less diversification benefit.

---

## 7. Normalised Price Comparison

Min-max normalisation was applied to compare price movements on a common scale.

<img width="3466" height="1520" alt="normalised_stock_prices" src="https://github.com/user-attachments/assets/fd20b59c-221a-4a58-8108-4f1f0cd3284f" />


This allows assets with different price levels to be compared more fairly.

---

## 8. Log Transformation

Log transformation was applied to stock prices and returns to support time-series analysis and improve comparability.

<img width="3462" height="1520" alt="log_transformed_prices" src="https://github.com/user-attachments/assets/0f227b94-61e8-4931-b421-dcf5dae83cb7" />
<img width="3474" height="2739" alt="log_returns_histogram" src="https://github.com/user-attachments/assets/8ad77e35-8354-4ab1-90b8-79100e3f3db6" />



This transformation helps analyse proportional changes rather than raw price differences.

---

## 9. Moving Average Strategy

A moving average strategy was applied using short-term and long-term rolling averages.

<img width="3712" height="1109" alt="aapl_sma" src="https://github.com/user-attachments/assets/d08e36b6-7a0e-4129-9491-ab5a2f65d748" />
<img width="3712" height="1109" alt="amzn_sma" src="https://github.com/user-attachments/assets/c7d1940d-79ad-4ff2-af5c-c20f9519ec79" />
<img width="3712" height="1109" alt="cvx_sma" src="https://github.com/user-attachments/assets/bacd2906-9fe2-4c25-bc32-6c630b91b9fd" />



This demonstrates how Python can be used to create simple rule-based trading signals and evaluate market trends.

---

## Key Findings

- NVDA showed the highest annual mean return and strongest Sharpe ratio among the selected equities.
- Semiconductor and technology stocks generally produced stronger returns but also higher volatility.
- Energy stocks such as SHEL and XOM showed lower return levels but different correlation behaviour compared with technology stocks.
- Maximum drawdown analysis revealed that high-growth stocks can still experience substantial downside risk.
- Correlation analysis showed that some assets move closely together, reducing diversification benefits.
- Moving average analysis can help identify trend-following signals but should be tested carefully to avoid overfitting.

---

## Relevance

This project demonstrates practical skills in:

- Financial data analysis
- Python programming
- Time-series analysis
- Risk and return modelling
- Portfolio analytics
- Data visualisation
- Scenario-based financial analysis
- Decision-focused reporting

The project is relevant to finance data analyst, fintech, investment analytics, and business intelligence roles where financial datasets must be cleaned, analysed, and translated into clear insights.

---

## Future Improvements

- Add automated data pipelines
- Add SQL-based data extraction
- Add more advanced forecasting models
- Build an interactive dashboard version
- Include portfolio optimisation
- Add automated reporting outputs in Excel or HTML
