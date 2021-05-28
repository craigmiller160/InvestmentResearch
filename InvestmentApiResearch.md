# Investment Research

This is where I'm going to record everything that I need for my investment research.

## API Services

1. Tradier (https://api.tradier.com)
	1. Data is delayed 15 minutes.
	1. Only has Stocks & ETFs.
	1. Doesn't appear to be request limit.
1. Messari (https://data.messari.io/api)
	1. For Crypto data.
	1. Without key, requests limited to 20/minute and 1000/day.
	1. With key, requests limited to 30/minute and 2000/day.
	1. I think key is free.

## Stocks

### Goals

1. Current Stock Price
1. Historical Stock Price
1. Current Day Price Ticker

### Validation Symbols

1. AAPL (Apple)
2. CI (Cigna)


### APIs

1. Get Quote = Tradier = `GET /v1/markets/quotes?symbols=####,####`
1. Get Historical Quote = Tradier = `GET /v1/markets/history?symbol=#####&start=####-##-##&end=####-##-##`
1. Get Time & Sales (Today) = Tradier = `GET /v1/markets/timesales?symbol=#####&interval=5min&start=####-##-##&end=####-##-##`

## ETFs

### Goals

1. Current ETF Price
1. Historical ETF Price
1. Current Day Price Ticker

### Validation Symbols

1. VOO (Vanguard S&P 500 Index Fund)

### APIs

1. Get Quote = Tradier = `GET /v1/markets/quotes?symbols=####,####`
1. Get Historical Quote = Tradier = `GET /v1/markets/history?symbol=#####&start=####-##-##&end=####-##-##`
1. Get Time & Sales (Today) = Tradier = `GET /v1/markets/timesales?symbol=#####&interval=5min&start=####-##-##&end=####-##-##`

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

### Validation Symbols

1. BTC (Bitcoin)

### APIs

1. Get Market Data/Quote = Messari = `GET /v1/assets/btc/metrics/market-data`
1. Get Time Series (History & Today) = Messari = `GET /v1/assets/bitcoin/metrics/price/time-series?start=2020-01-01&end=2020-02-01&interval=1d`