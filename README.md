# FinancialModel
All syntax related to finance

# ETF assignment :

**Data Collection:**
Use Yahoo Finance to gather historical data for the ETF and its underlying assets. Use your discretion to pick a reasonable time frame.

**Python Implementation:**
Write a Python program that:

•	Reads the ETF's historical data from Yahoo Finance.

•	Based on the ETF's documentation and its investment strategy, simulate the ETF's returns over the given timeframe.

•	Generate the time series of the ETF's returns.

**Visualization:**

Generate plots that visualize the ETF's performance over time. Ensure your plots are clear, labeled, and easy to interpret.

**Analysis:**

Compare the replicated performance of the ETF with the actual performance data from Yahoo Finance.
Discuss any discrepancies or patterns you notice.

**Report Writing:**

Alongside your code and plots, prepare a brief report discussing your methodology, findings, and any challenges you encountered. This will help in understanding your thought process and the steps you took. 


# Final.ipnyb assignment :

-	Download the list of S&P500 firms from Wikipedia.

-	Download historical daily prices of the S&P500 firms from Yahoo! Finance.

-	Download all other data you need in later steps from appropriate sources. Such data include but may not be limited to

  o	Risk-free rates,
  
  o	S&P500 index prices and returns,

-	Convert all data to monthly frequency. You will only work with monthly data in this project.

-	Estimate the covariance matrix and expected returns of stocks every month. Your method of estimating the covariance matrices and expected returns must reflect two elements:

  o	The estimation methods we covered in class,
  
  o	An idea that you propose, based on your own thoughts or something you picked up outside the course material, to improve the estimation.

-	Form the tangency portfolio of S&P500 stocks using your estimates.

-	Calculate the Sharpe ratio for 

  o	Your tangency portfolio,
  
  o	An equally weighted portfolio of all S&P500 stocks,
  
  o	A tangency portfolio where all the covariances and expected returns are estimated using the Fama-French three factor model. (extra credit)

-	Write a report describing your results. In this report, you must include:

  o	A table of summary statistics for your monthly stock price data.
  
  o	A section explaining your method of estimating the covariance matrix and expected returns and arguing for its merit.
  
  o	A summary statistic table and a graph of the weights of stocks in your tangency portfolio; Feel free to select a few stocks for this step.
  
  o	A table and a figure describing monthly returns of your tangency portfolio.
  
  o	A table comparing the Sharpe ratios of the three portfolios above.
  
  o	A conclusion section explaining whether your proposed method works or not, and why.
