# js-ajax-excercise

- Script needs to calculate arbitrage opportunity between two bitcoin exchanges

## What is arbitrage?

`A situation in which dealers can make a profit because of the temporary difference in the value between two currencies in relation to a third currency.`
Source: http://lexicon.ft.com/Term?term=exchange-arbitrage 

## What to do?

- Fetch BTC Buy and Sell prices from BitBay exchange: https://bitbay.net/API/Public/BTCPLN/ticker.json
- Fetch BTC Buy and Sell prices from BitMarket exchange: https://www.bitmarket.pl/market.php?market=BTCPLN 
- Check if it is worth to buy BTC on one exchange and sell on another.
- Check where we should to buy and where to sell.
- If you are buying BTC - you need to check `ASK` price, when you are selling `BID` price.

## Layout:

- when you are loading the data - display `loading` infromation (using CSS Spinner)
- when you have the data, display Buy and Sell price from both exchanges
- as the last step, display where it is worth to buy and where to sell BTC
- Example interface: https://docs.google.com/spreadsheets/d/176E423tTNTje7oIZP8Ekwq1AQAwr5hYQECDxdZ78qSw/edit?usp=sharing 
