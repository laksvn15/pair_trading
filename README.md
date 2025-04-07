Pair Trading Strategy for US IT Stocks

This Python script checks 10 big US IT stocks and finds which ones move together (correlated) and are cointegrated. Then it:

+ Normalizes prices and compares the top 5 pairs  
+ Chooses the GOOGL–ACN pair to trade  
+ Creates signals based on beta-adjusted spread
+ Simulates trades (long/short) based on that signal  
+ Tracks returns, compares with S&P 500  
+ Finally, it calculates performance metrics like:
  - Sharpe ratio
  - Max drawdown
  - Alpha & Beta vs market
  - Profit factor

Libraries used are:
`yfinance`, `pandas`, `numpy`, `matplotlib`, `statsmodels`, `sklearn`
