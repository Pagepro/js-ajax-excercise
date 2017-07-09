# js-ajax-excercise

- Script needs to calculate arbitrage opportunity between two bitcoin exchanges

What to do?

- Fetch BTC price from BitBay exchange: https://bitbay.net/API/Public/BTCPLN/ticker.json
- Fetch BTC price from BitMarket exchange: https://www.bitmarket.pl/market.php?market=BTCPLN 
- Check if it is worth to buy BTC on one exchange and sell on another.
- Check where we should to buy and where to sell.
- If you are buying BTC - you need to check `ask` price, when you are selling `bid` price.

Layout:

- when you are loading the data - display `loading` infromation
- when you have the data, display Buy and Sell price from both exchanges
- as the last step, display where it is worth to buy and where to sell BTC

