# Stock Analysis
## Overview of VBA Project: 
- Our client, Steve, has requested a stock market analysis for the entire stock market and would like a easy button, similar to the one provided for the "All Stocks Analysis" workbook analyizing just 12 stocks.
- Using refactoring of the code behind the button to run faster, and handle a larger set of data, a new workbook allows for analysis of a larger data set.
- Using images and examples of code, below compares the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.
- Below shows the time to run pre-refactoring for the sample 12 stocks for each year
![InitialAllStocksAnalysis_2017](https://user-images.githubusercontent.com/90797036/135362997-6c878fe0-f44c-416b-8828-ccfea185d6cf.png)
![InitialAllStocksAnalysis_2018](https://user-images.githubusercontent.com/90797036/135363005-c8696acf-14d3-49a2-a204-c8036e38fc7b.png)
- Below shows rectoring shaved time off the macro
![VBA_Challenge_2017](https://user-images.githubusercontent.com/90797036/135728625-31899542-7bc2-48e6-911e-8d4cb8003992.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/90797036/135728627-fd240ff5-284d-4b6a-95b8-21d80018b79c.png)

## Summary: 
- In summary, we find that refactoring the macro to not use nested loops, and index the stock tickers, the code runs faster.
  - Thought difficult to find the best solution, once this code is completed the job is done.
  - Now Steve can simply use the button on the excel sheet to calculate total stock volumes, and the return.
  - Formatting allows Steve to quickly identify those stocks with positive returns, vs those with negative returns.
