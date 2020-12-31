"# pysystrader" 

focus on minimum viable product
first release - recreate alerting service - underlying price
get working locally , then add to AWS Lambda
next - alerts for options and spreads 


add UI section for picking stategies
lambda trading APIs (TradeKing, eTrade)
multiple strategies - indicator sets
report of strategies triggered
backtest strategy against stock 
which strategy worked best?
pair stocks with strategy
chart/graph overlay trangles on candlestick indicator
tradingview charts
import data
order placement - sandbox
track how sandbox orders did
database

vizualize:
Canvasjs : overlay? triangles? candlestick?
Data:
TradeKing
AlphaVantage https://www.alphavantage.co/
IEX https://iexcloud.io/docs/api/
QuanDL https://www.quandl.com/

Project: https://trading-bot.cassandre.tech/learn/technical-analysis
notes from https://cassandre.tech/
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
Freqtrade is a free and open source crypto trading bot written in Python. It is designed to support all major exchanges and be controlled via Telegram. It contains backtesting, plotting and money management tools as well as strategy optimization by machine learning.


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
Uses Flask! for dashboard

https://github.com/Drakkar-Software/OctoBot
Octobot is a powerful fully modular open-source cryptocurrency trading robot.
This repository contains all the features of the bot (trading tools, user interfaces, services, ...). Octobot's tentacles contains the bot's strategies.
To install OctoBot with its tentacles, just use the launcher and your OctoBot is ready !
wiki: https://github.com/Drakkar-Software/OctoBot/wiki

multipe exchange support
Digital Ocean Promo

https://github.com/sammchardy/python-binance
This is an unofficial Python wrapper for the Binance exchange REST API v3.

https://github.com/enigmampc/catalyst
https://enigmampc.github.io/catalyst/
Catalyst is an algorithmic trading library for crypto-assets written in Python. It allows trading strategies to be easily expressed and backtested against historical data (with daily and minute resolution), providing analytics and insights regarding a particular strategy's performance. Catalyst also supports live-trading of crypto-assets starting with four exchanges (Binance, Bitfinex, Bittrex, and Poloniex) with more being added over time.
Secure: You and only you have access to each exchange API keys for your accounts.

web: http://enigma.co/
web: https://www.catalystcrypto.io/
forum: https://forum.catalystcrypto.io/
website expired
discord: https://discord.com/channels/360051864110235648/360082867365216286

https://github.com/Roibal/Cryptocurrency-Trading-Bots-Python-Beginner-Advance
Hello and welcome to the code repository of @BlockchainEng Joaquin Roibal.
This Github Repository is used as a collection of python codes that you may find useful for making your own cryptocurrency trading bots or applying advanced trading strategies (Triangular Arbitrage, Market Making) to the cryptocurrency markets. Among other useful tools.
You may want to begin by watching my youtube video channel on introduction to crypto bot trading or advanced strategies such as triangular arbitrage, which will help you to understand the purpose and reasoning behind the code in this repo.
CRYPTO TRADING BOT VIDEOS: https://www.youtube.com/channel/UCVTnyT4fUxYkvawbggo8-AQ

https://github.com/ricequant/rqalpha
translate from chinese lol

https://github.com/CryptoSignal/Crypto-Signal
CryptoSignal - #1 Quant Trading & Technical Analysis Bot - 2,100 + stars, 580 + forks
Track over 500 coins across Bittrex, Binance, Bittrex, Bitfinex, Coinbase, Gemini and more!
uses ta-lib
discord: https://discord.gg/MWTJVFf

https://github.com/jasonstrimpel/volatility-trading
A complete set of volatility estimators based on Euan Sinclair's Volatility Trading.
http://www.amazon.com/gp/product/0470181990/tag=quantfinancea-20
Hit me on twitter with comments, questions, issues @jasonstrimpel
https://github.com/topics/volatility
https://github.com/topics/volatility-trading

https://github.com/tensortrade-org/tensortrade
TensorTrade is an open source Python framework for building, training, evaluating, and deploying robust trading algorithms using reinforcement learning. The framework focuses on being highly composable and extensible, to allow the system to scale from simple trading strategies on a single CPU, to complex investment strategies run on a distribution of HPC machines.

discord: https://discord.gg/ZZ7BGWh
gitter: https://gitter.im/tensortrade-framework/community

https://github.com/notadamking/RLTrader
Development on this library has slowed down, in favor of working on TensorTrade - a framework for trading with RL: https://github.com/notadamking/tensortrade
If you'd like to learn more about how we created this agent, check out the Medium article: https://towardsdatascience.com/creating-bitcoin-trading-bots-that-dont-lose-money-2e7165fb0b29
Later, we optimized this repo using feature engineering, statistical modeling, and Bayesian optimization, check it out: https://towardsdatascience.com/using-reinforcement-learning-to-trade-bitcoin-for-massive-profit-b69d0e8f583b

https://github.com/jchao01/TradingView-data-scraper
TradingView Chart Data Extractor
Video Tutorial
How-to screen recording: https://d.pr/v/VGCDNf

https://github.com/jesse-ai/jesse
Jesse is an advanced crypto trading framework which aims to simplify researching and defining trading strategies.
Why Jesse?
In short, Jesse is more accurate than other solutions, and way more simple. In fact, it is so simple that in case you already know Python, you can get started today, in matter of minutes, instead of weeks and months.
Here you can read more about why Jesse's features.

https://github.com/ivopetiz/algotrading
Algotrading Framework is a repository with tools to build and run working trading bots, backtest strategies, assist on trading, define simple stop losses and trailing stop losses, etc.

https://github.com/michaelchu/optopsy
Optopsy is a nimble backtesting and statistics library for option strategies, it is designed to answer questions like "How do straddles perform on the SPX?" or "Which strikes and/or expiration dates should I choose to make the most potential profit?"
Let's see how long calls perform on the SPX on a small demo dataset on the SPX: Download the following data sample from DeltaNeutral: http://www.deltaneutral.com/files/Sample_SPX_20151001_to_20151030.csv

https://github.com/kernc/backtesting.py
HUGE LIST of python algo resources

https://github.com/vsnz/TradingView-Webhook-Bot
very cool
The TradingView Webhook Bot ⚙️ listens to TradingView alerts via webhooks using flask. All alerts can be instantly sent to Telegram, Discord, Twitter and/or Email.

https://github.com/Ceruleanacg/Personae
Personae is a repo that implements papers proposed methods in Deep Reinforcement Learning & Supervised Learning and applies them to Financial Market.





https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github
StockTradingGraph.py
https://medium.com/@notadamking/visualizing-stock-trading-agents-using-matplotlib-and-gym-584c992bc6d4
https://github.com/wilsonfreitas/awesome-quant#trading--backtesting
https://github.com/topics/options-strategies
https://github.com/topics/options
https://github.com/topics/options-trading
https://github.com/topics/option-pricing
https://github.com/topics/option-strategies










