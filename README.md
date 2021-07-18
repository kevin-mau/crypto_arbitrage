# *Crypto Arbitrage*
---
When there is a price difference between two markets for the same asset, a profit opportunity arises.  To capitalize on the opportunity, you buy the asset from the lower priced market and then almost simultaneously sell it in the higher priced market.  This profit opportunity is called arbitrage.  

As an analyst of a high-tech investment firm, we are going to analyze market data from two cryptocurrency exchanges to examine if there were arbitrage opportunites within the two markets and the given time period.  We will gather data from Bitstamp and Coinbase, where we have the recorded daily prices of Bitcoin during the period from January 1st, 2018 through March 31st, 2018.

Here we will sort through the historical data and apply financial analysis through the power of Pandas.  I have created a Jupyter notebook that contains code for the data collection, preparation, and analysis.  Visualizations and commentary will also be included to go along with our findings.

Please review the report as the findings are quite interesting!  

---
## Technologies:

The Jupyter file utilizes python 3.7 along with the following libraries:

pandas

Path

matplotlib

```python
  import pandas as pd
  from pathlib import Path
  %matplotlib inline
```

## Data:

We will analyze two CSV files stored in the Resources folder: bitstamp.csv and coinbase.csv

These two CSV files contain historical market data of Bitcoin from each of the two markets from January 1st, 2018 through March 31st, 2018.

---

## Contributors

kevin-mau

---

## License

MIT