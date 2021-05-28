# Investment Research

This is where I'm going to record everything that I need for my investment research.

## API Services

1. Tradier (https://api.tradier.com/v1/)
	1. Data is delayed 15 minutes.
	1. Only has Stocks & ETFs.
	1. Doesn't appear to be request limit.

## Stocks

### Goals

1. Current Stock Price
1. Historical Stock Price
1. Current Day Price Ticker


### APIs

1. Get Quote = `GET /v1/markets/quotes?symbols=####,####`
1. Get Historical Quote = `GET /v1/markets/history?symbol=#####&start=####-##-##&end=####-##-##`
1. Get Time & Sales (Today) = `GET /v1/markets/timesales?symbol=#####&interval=5min&start=####-##-##&end=####-##-##`

## ETFs

### Goals

1. Current ETF Price
1. Historical ETF Price
1. Current Day Price Ticker

### APIs

TODO

## Mutual Funds

### Goals

1. Current Fund Price
1. Historical Fund Price

### APIs

TODO

## Crypto

### Goals

1. Current Crypto Price
1. Historical Crypto Price
1. Current Day Price Ticker

### APIs

TODO