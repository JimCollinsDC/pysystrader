"# pysystrader" 

add section for picking stategies
Project: https://trading-bot.cassandre.tech/learn/technical-analysis
notes from https://cassandre.tech/
External:
trading API
database

Bot:
Accountflux
Orderflux
Tradeflux
Tickerflux
Positionflux

Position Service:
OrderUpdate
TickerUpdate
TradeUpdate

Trade Service:
CreateMarketOrder
CreateStopOrder
CreateLimitOrder
CreateStopLimitOrder

"Cassandre will simulate valid exchange replies but won't execute them on the exchange. "

Notes for PyAlgoTrade
https://github.com/gbeced/pyalgotrade
Introducing AWS Step Functions.
looks good but not realtime

https://github.com/freqtrade/freqtrade
Freqtrade is a free and open source crypto trading bot written in Python.
Issues labeled good first issue can be good first contributions, and will help get you familiar with the codebase.
uses talib
follow up on this

website: https://www.freqtrade.io/
discord: https://discord.gg/MA9v74M
slack: https://join.slack.com/t/highfrequencybot/shared_invite/zt-jaut7r4m-Y17k4x5mcQES9a9swKuxbg

https://github.com/owocki/pytrader
pytrader is a cryptocurrency trading robot that uses machine learning to predict price movements at confidence intervals, 
and sometimes execute trades. 
3/20/2017 - This project has been put on ice by it's contributors. 

https://github.com/robcarver17/pysystemtrade
Systematic Trading in python
Rob Carver
https://qoppac.blogspot.com/p/pysystemtrade.html
Version 0.53.0
20201207
pysystemtrade is the open source version of my own backtesting engine that implements systems according to the framework 
outlined in my book "Systematic Trading", which is further developed on my blog.
https://qoppac.blogspot.com/
https://www.systematicmoney.org/systematic-trading
A series of examples using pysystemtrade for my blog posts can be found here.
https://github.com/robcarver17/pysystemtrade_examples

https://github.com/ranaroussi/qtpylib
QTPyLib (Quantitative Trading Python Library) is a simple, event-driven algorithmic trading library written in Python, 
that supports backtesting, as well as paper and live trading via Interactive Brokers.
Using pub/sub architecture using ØMQ (ZeroMQ) for communicating between the Algo and the Blotter allows 
for a single Blotter/multiple Algos running on the same machine.
Have orders delivered to your mobile via SMS (requires a Nexmo or Twilio account).
Full integration with TA-Lib via dedicated module (see documentation).
Ability to import any Python library (such as scikit-learn or TensorFlow) to use them in your algorithms.
Lastly, Your Strategies, which are sub-classes of Algo, handle the trading logic/rules. This is where you'll write most of your code.
website: https://aroussi.com/post/the-future-of-qtpylib

Supports multiple strategies





