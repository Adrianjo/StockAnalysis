# StockAnalysis
Stock Analysis written in Python


'''

Is this worth looking into?

https://github.com/jeog/TOSDataBridge/blob/master/python/tutorial.md

GitHub - jeog/TOSDataBridge: A collection of resources for pulling real ...
https://github.com/jeog/TOSDataBridge
TOSDataBridge (TOSDB) is an open-source collection of resources for pulling real-time streaming data off of TDAmeritrade's ThinkOrSwim(TOS) platform, providing C, C++, Java and Python interfaces. ... The core implementation is not portable, but the python interface does provides a thin virtualization layer over TCP.


'''

It looks like that library requires a local installation of thinkorswim. I have a TDAmeritrade account, and can download thinkorswim, but I don't think I can share the program.

I found [IEX Trading](https://iextrading.com/developer/docs/), an open access stock data API. It has real-time and historical timeseries data. It seems other people have already written libraries to use the API, including six written in Python. We could look through those and see which is flexible enough for our uses.

**JOR**

'''

'''

I have thinkorswim now, it was pretty easy to sign up and you don't have to load any cash in at first. Until you load money in, all stocks are 20 minutes behind but that wouldn't be too big of a problem during development.

I've heard mixed things on IEX but I'd be willing to try anything. People keep saying pandas_datareader works with new code but I cannnnnnot get it to work. I've updated all of my packages and tried all sorts of things. Let me know if you get pandas_datareader to work. I've been using 'pip3 install' to insure I have the Python 3 versions.

JMO

'''
