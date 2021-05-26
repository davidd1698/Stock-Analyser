# Stock-Analyser


The program will ask the user to input the number of stocks he wants to select, the ticker of each stock, the start and end dates and the risk free rate and checking that those inputs are usable by the program, the program will do several things: 

First, the program will scrape data on the stocks selected from Yahoo finance in order to display some informations about them. Those informations include data from the balance sheet, the income statement and the statement of cash flows of each company. They will be summarised in a single table which will display date for several periods. 

Second, the program will display the normalized closing prices and volumes of each stock selected on two graphs. Moreover, additional data about the closing price of each selected stock will be displayed in a table. This allows the user to rapidly compare the different stocks selected.

Third, based on a simulation of 7500 portfolios, the program will compute the weights the user should attribute to each stock in his portfolio to generate the minimum variance portfolio, the maximum Sharpe ratio portfolio, and the maximum return portfolio. 

Last, the program will give the user some risk metrics about each of the aforementioned portfolios in order to help him make an investment decision. The information displayed here is the variance, the standard deviation and the volatility of each portfolio.

After using our program, the user should have gained enough information about the companies selected and the different stocks combination possibilities to make an informed investment decision.
