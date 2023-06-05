# Background
Here we assume the role of a quantitative analyst for a FinTech investing platform. This platform aims to offer clients a one-stop online investment solution for their retirement portfolios that’s both inexpensive and high quality. (Think about WealthfrontLinks to an external site. or BettermentLinks to an external site.). To keep the costs low, the firm uses algorithms to build each client's portfolio. The algorithms choose from various investment styles and options.

The task is to evaluate four new investment options for client portfolios. Legendary fund and hedge-fund managers run all four selections. (People sometimes refer to these managers as whales because of the large amount of money that they manage). Here we determine the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

# What's being Created
A Jupyter notebook that contains prepared data, analysis, and visualizations for key risk and return metrics. 

Specifically:
+ A single DataFrame imported from a CSV file that has a DateTimeIndex.
+ A risk analysis of the assets that the DataFrame contains vs. the S&P 500. This analysis should include risk-return metrics, including the daily returns, standard deviation, Sharpe ratio, and beta.
+ An evaluation of each asset that uses rolling statistics to track the risk-reward behavior over time.