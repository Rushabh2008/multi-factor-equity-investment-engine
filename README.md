

Multi-Factor Equity Investment Engine
Overview

This project investigates whether a systematic factor-investing strategy based on Value, Momentum, and Quality factors can outperform the broader stock market.

Using Python and historical market data from Yahoo Finance, stocks were ranked according to valuation, price momentum, and financial quality metrics. The highest-ranked companies were selected to construct a portfolio which was then compared against the S&P 500 benchmark.
METHODOLOGY
1 ) Value Factors
-Price-to-Earnings Ratio (P/E)
-Price-to-Book Ratio (P/B)

2) Momentum Factors
-3-Month Return
-6-Month Return
-12-Month Return

3) Quality Factors
-Return on Equity (ROE)
-Profit Margin

Portfolio weights:
Value: 40%
Momentum: 30%
Quality: 30%

Results
Metric	Result
Annual Return	25.98%
Annual Volatility	22.00%
Sharpe Ratio	1.18
Maximum Drawdown	-39%
Thus, The factor portfolio outperformed the S&P 500 benchmark over the testing period.

Technologies Used
Python
Pandas
NumPy
yFinance
Matplotlib
Seaborn

Key Learning Outcomes
Financial Data Analysis
Factor Investing
Portfolio Construction
Backtesting
Quantitative Research
Risk Analysis
