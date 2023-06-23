# algo-trades
Steps followed: 
1) Select Stocks whose closing price is higher than their SMA for a defined period (200 days,50 days, etc.).
2) Calculate the optimum weight ratios for the stocks using either Mean-Variance Optimisation or other methods defined in the PyPortfolioOpt library.
3) Invest the portfolio according to the weights assigned.
4) Repeat the process for the required rebalancing frequency.
5) Generate a detailed strategy analysis report using quant-stats library.
   


Optimizing the given strategy to achieve better trading results:
1) Changing the SMA period
2) Changing the rebalancing frequency
3) Changing the lookback period
4) Changing the asset allocation models (available within PyPortfolioOpt)
5) Changing commission rates - flat rates/percentage rates.



