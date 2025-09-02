# CPI-Analysis-and-Recession-Probability-Forecast
This project analyzes the relationship between inflation (CPI), S&P 500 performance, and recession probability using data from the FRED API and Yahoo Finance.


It combines multiple economic indicators into a single dataset and explores:
Inflation-adjusted S&P 500 performance
Treasury yield curve spreads
Recession probabilities (from the Federal Reserve)

### The goal is to provide insights into how inflation and interest rate dynamics affect market performance and recession risks.

**Data Sources**
Consumer Price Index (CPI): CPIAUCSL
  10-Year Treasury Yield: DGS10
  3-Month Treasury Yield: DGS3MO
  3-Month Treasury Yield (Bond Equivalent): DTB3
  Recession Probability: RECPROUSM156N
Yahoo Finance:
S&P 500 Historical Data: ^GSPC

**Features**
Fetch CPI and calculate inflation-adjusted S&P 500
Retrieve Treasury yields and compute yield spread
Add Recession probability and NBER recession periods
Combine all into one master dataset
Perform time-series analysis & visualization
