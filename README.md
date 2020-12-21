# Bybit dataset download
Simple script to download historical data from [Bybit](https://www.bybit.com/). The scripts downloads all candlestick data for a given period and save it in a csv file.

## Usage
Inside the `download.py` file in the first lines after `if __name__ =='__main__:`
you can change the following configuration:

```python
start = '01-03-2019 00:00' # Date in the format day-month-year hour:minute
end = '01-09-2020 00:00' # A valid date or None for the current date
currency_pair = 'BTCUSD' # Currency pair that will be traded
interval = 1 # valid values are: 1,3,5,15,30
```

+ you also need to install the required dependencies running `pip install -r requirements.txt`
Everything is setup, you can run the code with `python3 src/download.py`

