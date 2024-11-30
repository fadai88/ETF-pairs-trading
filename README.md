The investment universe consists of 22 international ETFs. A normalized cumulative total return index is created for each ETF (dividends included), and the starting price during the formation period is set to $1 (price normalization). 
The selection of pairs is made after a 120 day formation period. Pair’s distance for all ETF pairs is calculated as the sum of squared deviations between two normalized price series. The top 5 pairs with the smallest distance are used in the subsequent 20 day trading period. 
The strategy is monitored daily, and trade is opened when the divergence between the pairs exceeds 0.5x the historical standard deviation. Investors go long on the undervalued ETF and short on the overvalued ETF. 
The trade is exited if a pair converges or after 20 days (if the pair does not converge within the next 20 business days). Pairs are weighted equally, and the portfolio is rebalanced on a daily basis.

https://quantpedia.com/strategies/pairs-trading-with-country-etfs/
