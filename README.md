# YahooFinanceWebCrawler
Get Historical Stock Data from Yahoo Finance

## Usage
1). Download YahooFinanceWebCrawler.ipynb  
2). Run the notebook  
3). Call GetHistoricalData with stock price, start date, end date, and frequency to get data.  

## Example
```python
stock = 'GOOG'
start = 02/01/2005
end = 02/01/2019
frequency = 'daily'   #'daily' / 'weekly' / 'monthly'
df = GetHistoricalData(stock, start, end, frequency)
df
```
