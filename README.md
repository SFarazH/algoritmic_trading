## Algorithmic Trading

#### Quantitative Momentum Strategy
This is a model that selects the top 50 stocks based on factors such as :
<br>`1 month price returns`
<br>`3 month price returns`
<br>`6 month price returns`
<br>`1 year price returns`

For all of these factors, average percentile is calculated for each stock.
According to this, top 50 stocks are selected as **High-Quality Momentum** stocks.
We take into consideration factors other than 1 year price return, as that alone can be misleading.

Dataset of `S&P500` (America's top 500 stocks) has been used using `IEX CLOUD LEGACY API`.
