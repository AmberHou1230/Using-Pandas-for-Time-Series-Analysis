# Using-Pandas-for-Time-Series-Analysis

Time series analysis using Pandas and Yahoo Finance data

## Key discussions & takeaways:
1. Why does "Close" and "Adj Close" differ at "the beginning of time"? Notice that in recent years, "Close" and "Adj Close" are the same. So why did it differ before?

2. Plot daily returns. Observations?
  - There are periods where the market is more volatile. calm periods and volatile periods.
  - 1997 financial crisis
  - 1998 what happened? There was a long term capital management blow-up. There was a hedge fund called Long Term Capital Management. They owned a lot of bonds that were illiquid. So if they go bankrupt, it's going to cause severe destruction in the economy, they got bailed-out.
  - 2000 dot-com bubble where tech companies were worth too much, caused a lot of volatility. the dot com bubble didn't burst until Oct 2002. It is interesting to know that (we can also see this in the graph above) the volatility peaked in July, but the market then went to bottom after July. There was a period of peak panic when everything was dropping lower and lower and lower but nobody was actually selling, adn then a year from 2002 was the best time to buy.
  - March 2003, pandemic
  - before 2008, there was a "smooth" period when people are buying multiple houses, by just relying on income they could get the loans anyways.
  - 2008 financial crisis, volatility peaked in Oct 2008. Peak panic,following by a period where people were slow to sell or selling at small volumes.
    - Volatility is the double-edge sword. we can see that the best days of the market is also around the time of the worst days of the market.
    - Best advice is probably to cut your position to somewhere you can still sleep at night but not be completely out, because you don't want to miss the best day of the market of the last 30 years just by avoiding the worst days. plus, you might already got hit by the worst days.
    - May 2010, there was a [flash crash](https://www.theguardian.com/business/2015/apr/22/2010-flash-crash-new-york-stock-exchange-unfolded) that spooked the market for 36 minutes.
  - 2011 European financial crisis, Brexit
  - 2020 COVID Pandemic

3. Calculate the volatility of SPY daily returns.
4. Calculate the Rolling 1 Month (21 days) volatility of the S&P 500 ETF, SPY
5. Learn how to forward fill "missing days"
6. Seasonality analysis - Are Mondays more volatile than other days?
