# CoinGeckoPortfolio-MoneyMoney
Inofficial CoinGecko Extension for MoneyMoney

## Setup

1. Download the extension via [GitHub](https://github.com/conradreisch/CoinGeckoPortfolio-MoneyMoney/blob/main/CoinGeckoPortfolio.lua)
2. Once downloaded, move `CoinGeckoPortfolio.lua` to your MoneyMoney Extensions folder.
3. Add a new account with the type `CoinGeckoPortfolio`
4. Include your coin portfolio in MoneyMoney by providing the coin ids and the amount of coins as username. Example: `POLKADOT(10),CARDANO(100)`

### Bonus
Add the buying rates in MoneyMoney via right click on the stock to display the profits.

### Known Issues

CoinGecko is using rate limits for guest users. Those rate limits seem to change from time to time.  
In case you run into a `HTTPS response: Too Many Requests` issue, you might want to set the delay (in ms) manually, followed by a semicolon. Example: `DELAY(12000);POLKADOT(10),CARDANO(100)`

### Requirements
You need at least version 2.4.x or a beta version of MoneyMoney.
