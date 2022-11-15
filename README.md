# power_query_python_equivalent
Creating a Python equivalent to query, structure, and analyze stock fundamentals


For our Power Query workshop, we use Power Query and Microsoft Excel to merge and analyze data on the fundamentals of a number of companies. 

I have created a Python notebook that does an equivalent. It queries the data from Yahoo Finance using the `yahoo_fin` library, melts and shapes it correctly, calculates desired fields, and plots these for each company. 

The central creation is the `fundamentals_querier()` function, which can be fed a list of any stock tickers the library can access, and returns the cash flow, balance sheet, and income statement of each company for the four most recent years. The rest of the notebook runs all the way through without modification, though my example uses big tech stocks, so some variable and plot names may not match. 

The only notebook here will be `query_function.ipynb`, which includes this function and sample analysis. 
