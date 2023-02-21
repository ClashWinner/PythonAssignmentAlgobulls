# PythonAssignmentAlgobulls
Simple Algorithmic Trading Strategy

Every Class can run as said in documentation

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
