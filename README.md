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
- By comparing 2017 and 2018 data analysis we can make below conclusion:
![Comparison_Chart](https://github.com/reza-ya57/Stock-analysis/blob/main/Resources/Performanc_Stock_Comparison.png)
    - By looking at yearly return percentage we can say 2017 has better performance than 2018
    - 
by preparing summary report in total daily volume for 2017 and 2018 based on the yearly return for these 12 stocks. Total daily volume can show him how actively the stocks was traded and the yearly return shows the percentage increase or decrease in price from the beginning of the year to the end of the year.

