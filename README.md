# Calculating Risk Return Beta Sharpe and Comparing Portfolios using Pandas
### Outline

Consider all csv data files resides in "Resources" directory which is placed with in this directory. Code resides in the whale_analysis_sen.ipynb file which resides in the same directory.

The whale_analysis_sen.ipynb code has two parts.

#### Part 1.
This will read the csv files from: 
a. returns of a collection of whale investor portfolios (Soros Fund, Paulson Fund, Tiger Global Fund, Berkshire Fund)
b. returns of a two Algorithmic Traders (Algo 1 Fund and Algo 2 Fund)
c. closing price of S&P 500 Index 

First the code will clean the data, format the data, get returns (for the S&P 500) and read them into a DataFrame. 

Using the Python Pandas code will then perform a Portfolio Performance Analysis. This include calculate, plot, and analyze daily returns and cumulative daily returns over the period of the individual portfolios over the given period.    

Using Python Pandas code will then do a Portfolio Risk Assesment. This includes calculate, plot, and analyze the individual daily returns of the portfolio by box plots, standard deviation, annualized standard deviation, correlation matrix, correlation heat map, static beta (for the entire period), dynamic rolling beta (21-day), and Sharpe ratios.  

#### Part 2.

This will read the csv files from: 
a. closing price of AAPL (Apple Inc.) 
b. closing price of COST (Costco Inc.)
c. closing price of GOOG (Google Inc.)

First the code will clean the data, format the data, calculate daily returns for each security and read them into a DataFrame. 

Then the securities will be wighted equally (this can be tuned as needed) to create a Select Portfolio. This Select Potfolio will be added to the previous Portfolio collection for comparison analysis.

Using Python Pandas code will then do a Portfolio Risk Assesment. This includes calculate, plot, and analyze the individual daily returns of the portfolio by standard deviation, annualized standard deviation, correlation matrix, correlation heat map, static beta (for the entire period), dynamic rolling beta (21-day), and Sharpe ratios

Using the Python Pandas it will then perform a Portfolio Performance Analysis. This include calculate, plot, and analyze cumulative daily returns over the period of the individual portfolios over the given period.    

These will be used to for analysis and comparion of each portfolio over their performance and risk. 

### Inputs
Read in returns as csv files of whale portfolio and algorithmic portfolio. Read in closing prices as csv files of s&p 500, aapl (Apple Inc.), cost (Costco Inc.), goog (Google Inc.). 

### Outputs
Outputs are given out as mentioned above the outputs are displayed on the terminal calculation values, visual plots/graphs/figures, and analysis commentary derived from them. 

### Remarks
The inputs files have "$" sign and some has reverse order which needed formating. 
