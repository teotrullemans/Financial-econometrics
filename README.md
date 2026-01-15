# Equity Stylized Facts – Morgan Stanley (MS)

## Objective
Empirical verification of key stylized facts in equity return time series using Morgan Stanley (MS) daily stock data.

The analysis covers the main stylized facts documented in the financial econometrics literature (Cont, 2001).

## Stylized Facts Covered
1. Prices are non-stationary  
2. Returns are stationary  
3. Returns are asymmetric  
4. Returns exhibit heavy tails  
5. Aggregational Gaussianity  
6. Returns show little or no autocorrelation  
7. Volatility clustering  
8. Leverage effect  

## Data
- Asset: Morgan Stanley (MS)
- Frequency: Daily prices
- Market: NYSE (United States)
- Source: Yahoo Finance via `yfinance`
- Sample period: configurable in the notebook

## Methodology
- Log-return construction
- Stationarity tests (ADF)
- Distribution diagnostics (skewness, kurtosis, Jarque–Bera, QQ-plots)
- Autocorrelation analysis (ACF, Ljung–Box)
- Volatility clustering via squared/absolute returns
- Leverage effect via cross-correlation and volatility proxies

## Tools
Python: pandas, numpy, scipy, statsmodels, matplotlib, seaborn

## How to run
Open and run the notebook:
`Equity_Stylized_Facts_MS.ipynb`

## Authors
Christiane Diop and Téo Trullemans 
