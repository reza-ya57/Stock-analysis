# Analyze Stock Data
## Overview of Project
### Steve wants to find the best stock in market for investing and he collects two years data records of 12 stocks in the market. In this project we Help him on decision making process.  Steve also wants to have a high performance code in case he want to use this code for large amount of data in future so we prvide the performance measurment in this project to verify the ability of the code for big data and also we refactor the code to improve the process time.

## Result
### To refactor the code we used array variable and put all process in one loop to prevent multiple process and reduce the output time. 
- In this project we used array variable to record stock name and value so we assign a 12 size array regarding the total number of stocks.
```
Dim tickers(12) As String
        
```
- We determine three below arrays to collect the result and pass to the analyze report
``` 
    Dim tickerVolume(12) As Long
    Dim tickerStartingPrice(12) As Single
    Dim tickerEndingPrice(12) As Single
```
### We calculate total daily volume and yearly return for these 12 stocks on 2017 and 2018 based. Total daily volume can reveal how actively the stocks was traded and the yearly return shows the percentage increase or decrease in price from the beginning of the year to the end of the year.

![Comparison_Chart](https://github.com/reza-ya57/Stock-analysis/blob/main/Resources/Performanc_Stock_Comparison.png)

- By comparing 2017 and 2018 data analysis we can make below conclusion:
  - By looking at yearly return percentage we can say 2017 has better performance than 2018. In 2017 only one of the stock has negative return and the others have positive outcome. 
  - Based on 2018 result two stocks have a better performance and could be a candidate for investing, ENPH and RUN
### By refactoring the code we achieved a significant improvement in excecution times. You can see the executiontime of original code and refactored script below:

![Original_Excecution_Time](https://github.com/reza-ya57/Stock-analysis/blob/main/Resources/Excecutive_Time_2017_Original.png)
![Refactor_Excecution_Time](https://github.com/reza-ya57/Stock-analysis/blob/main/Resources/Excecutive_time_2017_Refactor.png)

## Summary
- Advantages of refactoring code
  - Have compact code
  - Reduce memory usage
  - Decrease required storage

- Disadvantages of refactoring code
  - Increase complexity of the code
  - Take more time 

### To refactor the original code in this project we eliminate non essential loop and used single loop for the whole process. This change cuased more complixity to find the solution to run the script with one loop. In other hand by using this method the script line decreased and also the execution time improved. 
### In summary refactoring is required for high performance script regarding to run the code in large data so we can have a significant improvement by reduce the memory usage and increase the execution time. 
