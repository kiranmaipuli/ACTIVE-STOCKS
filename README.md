This project displays the data of the most active stocks. The CNN Money's Market Movers website tracks the most active, top gainers, and top losers at any instance of time. The ticker symbols and names of each company are extracted in the order and categories listed from the Money Market Movers website using Python and Beautiful Soup library and stored in the stocks_data.csv file.

For each stock in stocks_data.csv, the following details are extracted from finance.yahoo.com and stored using Pandas data frame while preserving the order
1. OPEN price
2. PREV CLOSE price
3. VOLUME
4. MARKET CAP
