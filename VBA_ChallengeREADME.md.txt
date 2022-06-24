#Overview of Project
##Helping Steve
This project was to create a tool that would allow my friend Steve to be able to analyze the entire stock market over a two-year period. He wanted to be able to do this to best help his parents make a sound investment decision. The original workbook could do twelve stocks at once, but this refactored code can do the entire market. 

#Results and Outcomes


##Results of Findings 
After running the code for both 2017 and 2018, the first year shows a positive return in all but TERP stock. However, 2018 only shows a positive return in ENPH and RUN stocks. Based on this two year comparison, these two stocks seem to be the best investment for Steve and his parent. 

Below the code shows the changes made to have to workbook run faster as well as use more data. This was accomplished by taking advantage of nesting loops and creating four arrays; �tickers�, �tickerVolumes�, �tickerStartingPrices�, and �tickerEndingPrices�. With the use of a created variable �tickerIndex� the data could be ran much more efficiently.  

2017 stocks.png
stocks_2018.png

#Summary
##Pros and Cons of Refactoring
The largest benefit of refactoring code is the increase in overall efficiency. The largest downside is the risk of overcomplicating and possibly breaking an already working code. But, if the one writing it is careful, the good far outweighs the bad.
##Original vs Refactored 
The original code was easier to program and explain to the user or person that were to come behind you. But the refactored code was more front side user friendly and ran even faster. 
