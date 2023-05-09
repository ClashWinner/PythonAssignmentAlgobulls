# PythonSimpleTradingStrategy
Simple Algorithmic Trading Strategy

Task 1 Get The Data:

- Get the Data from Alpha Vantage API
- Fetch the data by function fetch_intraday_data()

- Convert the Data into Required Data Types convert_intraday_data()
     i. timestamp (data type: pandas.Timestamp)
    ii. open (data type: float)
    iii. high (data type: float)
    iv. low(data type: float)
    v. close (data type: float)
    vi. volume (data type: int)
    
Task 2 Creating Indicator indicator1():

- Moving Average of Closing Price with Timeperiod of 5

Task 3 Creating Strategy():

- Give Buy and Sell Signals based on 'Cut Upwords' and 'Cut Downwords' movements of current price to the Moving Average provided by indicator1()

Task 4 Plotting Candlestick chart:

 - Class Candlestick is created to plot the candlestick chart
 - __init_() constructor fetches the required data frames fron the class ScriptData
 - candlestick() function is generating the candlestick chart
 - creating instance of Candlestick class with providing script(Stock Name) parameter
      ex: 
           candlestick_chart = Candlestick('NVDA')
 - Then Call the candlestick function with class instance
      ex:
           candlestick_chart.candlestick()
 - Candlestick chart will get Ploted 
