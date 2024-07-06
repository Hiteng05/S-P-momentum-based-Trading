# Algorithmic Trading in Python
Here we execute a momentum based strategy to trade on the S&P500 stocks.
We Derive past prices and data of the stocks, and based on that determine which stocks have given the best return in the recent past (i.e have high momentum) and are still likely to keep going up, we do this using the python script.
Then we idetify the top 50 high momentum stocks out of the 500, and distribute our investment amount equally amongst them.

## Modules and APIs used
- IEX Cloud API was used to get the current as well past data of the stock prices.
- requests module was used to execute these requests to the API.
- Numpy , pandas and built-in python tools were mainly used to do all the calculations and processing.

## Scope for expansion 
- An automated trading system can be made which uses APIs to automatically execute these order at the market.
- Such a system can be expanded to include other strategies like MACD or TEMA , or even Machine Learning algorithms.
