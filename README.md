Quanturf's Datasets - Free Financial data for building Financial models
==========================================================================================

This documentation contains the information about the **Free financial dataset** for thousands
of asset classes, macroeconomic data, fundamentals and alternative data that can be used for building algo-trading models on [Quanturf](http://quanturf.com/).


This doumentation shows you how to get massive amounts of Financial Data and explains how to **install required Libraries** and how to **download/import the data** with few lines of Python Code.

The data covered in this documentation include:
-----------------------------------------------
- Historical Price and Volume Data for 100,000+ Symbols/Instruments.
- 50+ Exchanges all around the world.
- Real-time and Historical Data (back to 1960s)
- High-frequency real-time Data
- Foreign Exchange (FOREX): 150+ Currency Pairs
- 500+ Cryptocurrencies
- Commodities (Crude Oil, Gold, Silver, etc.)
- Futures and Option data
- Macroeconomic variables
- Stock Options, Stock Splits and Dividends for 5000+ Stocks
- Fundamentals, Metrics and Ratios for Stocks, Bonds, Indexes, Mutual Funds and ETFs
- Balance Sheets, Cashflow and Profit and Loss Statements (P&L)
- 50+ Technical Indicators (i.e. SMA, Bollinger Bands).

Financial Data types covered:
-------------------------------------------------

-   Equities
-   FixedIncome
-   FX
-   Commodities
-   Crypto
-   Fundamentals
-   OptionFuture
-   Macroeconomic
-   Sentiments
-   AlternativeData


Financial Data source covered:
-------------------------------------------------

Seperate notebook for each different library has been included. 

-   YahooFinance
-   Alphavantage
-   FundamentalAnalysis
-   quandl
-   FRED
-   Stooq
-   IEX
-   Oanda
-   finviz
 


Contributing
------------

To any interested in making the FinAIML better, there are still some improvements
that need to be done.
A full TODO list is available in the `roadmap <https://github.com/users/tatsath/projects/4>`_.

If you want to contribute, please go through `CONTRIBUTING.md <https://github.com/Quanturf/quanturf_dataset/blob/master/CONTRIBUTING.md>`_ first.

Indices and tables
-------------------

* :ref:`genindex`
* :ref:`search`
* :ref:`modindex`


### Our Recommendation

* We prefer yfinance for technical analysis, because it has an easy-to-use API and very convenient most of the times.

* For Fundamental analysis, FundamentalAnalysis package is the best, as it requires no data cleaning and can be used directly to get detailed financial statements of a company, however it has coverage limitations and doesn't cover a lot many stock exchanges, so you can choose between Web Scraping and FundamentalAnalysis package as per your requirement.
