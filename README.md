# python-trading-bot
Binance basic RSI trading bot with TP and SL

# if you're feeling generous and want to support me:
BTC adress:bc1qma8sspr5hxggzyu5atfm33tldumwmj0w5n54ue

BNB adress:bnb14z584d3d5d0uxf3tdhh4sr8gryaw6j9htcptzf

ETH adress:0x9F925CA2293ED1CB9Dd6Ab65Ca14A4Ea07511673

# Use bot at own risks cryptocurrencys are volatile assets and traders accounts are at risks. None of this is financial advice nor is it guidence on how to trade just a software I created for fun, not for retail use. Do not use this software as a way to make money as the strategy is not proven so your capital is at risk it is not reliable trading strategy.

Code is in Microsoft Word file so download file, copy and paste code into your python script and run.

Code is raw

# To change bots take profit and stop loss edit:
profit = 0.01
this means take profit is set at 1%

loss = 0.015
this means stop loss is set at 1.5%

edit tese values to change to desired take profit and stop loss.

# RSI settings 
RSI_PERIOD = (14 good tested value)
RSI_OVERBOUGHT = (70 good tested value)
RSI_OVERSOLD = (30 good tested value)

# Settings for traders symbol and quantity
quantity is based off of the first cryptocurrecy symbol
eg: 0.00027 = BTC at a value of $7.98 as of 10/06/2022

TRADE_SYMBOL = 'BTCUSDT'
TRADE_QUANTITY = 0.00027 

# API keys
here input the traders API key and secret Key found on binances API page under profile
API_KEY = ''
API_SECRET = ''

# Find trade quantities for chosen trading pair to see minimum trading quantity
(average is $10 on binance i think)
input trading pair where TRXUSDT is which is the example

info = client.get_symbol_info('TRXUSDT')
print(info)
print(info['filters'][2]['minQty'])

# Input trading pair
here input chosen trading pair where ["btcusdt"] is 
input time frame where @kline_1m is. 1m means 1 minute time frame and can be changed to whichever time frame chosen

subscribe_message = {"method": "SUBSCRIBE", "params": ["btcusdt@kline_1m"], "id": 


Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the 
Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the 
Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIM

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A 
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION 
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.




