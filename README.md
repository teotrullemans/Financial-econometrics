# Financial-econometrics
Empirical analysis of equity returns and asset pricing models in Python
Objective
Empirical verification of key stylized facts in equity return time series using Morgan Stanley (MS) daily stock data.

The analysis covers the main stylized facts documented in the financial econometrics literature (Cont, 2001).

Stylized Facts Covered
Prices are non-stationary
Returns are stationary
Returns are asymmetric
Returns exhibit heavy tails
Aggregational Gaussianity
Returns show little or no autocorrelation
Volatility clustering
Leverage effect
Data
Asset: Morgan Stanley (MS)
Frequency: Daily prices
Market: NYSE (United States)
Source: Yahoo Finance via yfinance
Sample period: configurable in the notebook
Methodology
Log-return construction
Stationarity tests (ADF)
Distribution diagnostics (skewness, kurtosis, Jarque–Bera, QQ-plots)
Autocorrelation analysis (ACF, Ljung–Box)
Volatility clustering via squared/absolute returns
Leverage effect via cross-correlation and volatility proxies
Tools
Python: pandas, numpy, scipy, statsmodels, matplotlib, seaborn

How to run
Open and run the notebook: Equity_Stylized_Facts_MS.ipynb

Authors
Christiane Diop and Téo Trullemans
