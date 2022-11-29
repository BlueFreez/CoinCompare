# CoinCompare

Website that uses public API of cryptocurrency exchanges to find lowest buying price and arbitrage opportunities

For more details regarding arbitrage and how our website works, visit [this article](https://medium.com/@namrapatel26/arbitrage-in-cryptocurrency-trading-fe5e177c46d2)

Link to website hosted on Heroku [https://coin-compare-17.herokuapp.com/](https://coin-compare-17.herokuapp.com/)

Demo of the website is available [here](https://youtu.be/Kjy9D0oRiWg)

Postman Collection for our API requests is [here](https://www.postman.com/vmnbits/workspace/team-workspace/request/19265479-1f065160-ba8d-4e0a-be44-f246e0de0711)

[Here](https://drive.google.com/file/d/1BXxaAbc_iogCYM59OSezcBrqz0vbK-12/view) is the use case of postman in development process 

## Further ahead

- We only included 5 coins and 4 exchanges due to time constraints, but this could be expanded to include all coins and exchanges. We'd need to create a parser for API calls for the corresponding coins and exchanges, as well as verify each exchange's cost structure.
- Next, we'll build a batch application with a tracker that will notify users via email or text message about any arbitrage opportunities.
- Furthermore, all of this could be automated, with users buying from one exchange and selling from another, but all of this would require authentications from all different exchanges and bank accounts in order to transfer funds and assets.

## To run the website

Use these commands to run the website. It will be available at [http://localhost:3000/](http://localhost:3000/)

```bash
npm install
npm start
```

Arbitrage in Cryptocurrency Trading
What is ‘arbitrage’?
In simple terms, arbitrage is taking advantage of a difference in prices of securities, stocks, currencies, or commodities in two or more markets. For example, gold may be traded on both London and Tokyo stock exchanges, or Tata Motors is traded on both NSE(National Stock Exchange) and BSE(Bombay Stock Exchange). If you are coming from a trading background, all of these must seem very familiar!

Let’s look at an example to see arbitrage in practice:
The cost of 1 unit of Tata Motors stock at NSE is 456. At the exact moment in time, the price of 1 unit of Tata Motors at BSE is 452. If someone was to purchase 2000 shares of Tata Motors from BSE and sell it in NSE, that trader would have gained 4 rupees profit on each share. For 2000 shares, this results in a profit of 2000x4=8000 rupees of profit. Per unit, profit might be small, but the trade has a capacity of delivering profit at low risk.


Even for cryptocurrency arbitrage, the concept remains similar. You buy a crypto asset on one exchange and sell it simultaneously on other where the price is higher to generate low-risk profits.

How does it work in crypto markets?
The crypto market is highly volatile compared to other financial markets. Crypto prices tend to deviate significantly over a certain period of time. Also, they are traded globally across hundreds of exchanges 24/7. Still, the critical question remains unanswered, why the disparity in prices among different exchanges?

First, we need to understand how the prices are determined by crypto exchanges. As a universal rule, supply and demand determine the value of every item, and cryptocurrencies are not an exception. Other factors also influence the prices, which might indirectly affect their market value. These factors are the cost of mining crypto coins, rewards issued to miners, regulations governing its sale, and many more. So, however ironic it may sound, the crypto exchanges don’t set the price. They only provide a framework for customers to buy and sell coins at whatever prices the buyer and seller find mutually agreeable. The exchange itself does not buy or sell. The prices it quotes are just the report of what trade the customers are making at that very moment.


This particular decentralized system generates possibilities for arbitrage trading. There will always be differences in demand and supply for various crypto assets on different platforms. The difference in value might not be significant enough every time to make substantial profits, but we have tried to develop a solution for that. We have developed an app that can help you discover such opportunities whenever they arise. Let me show you how it works, and you can thank me later!

The CoinCompare App
The CoinCompare app lets you compare the prices of each cryptocurrency on different exchanges. It provides information about the trade between which two platforms would be most profitable for a particular coin. The app provides the results not only based on price differences among platforms but also considers various fees that you might incur when buying and withdrawing coins. The app calculates the total cost of executing the arbitrage trade, from buying the coin from one exchange to transferring it into the wallet of another platform and finally withdrawing the amount from your wallet into your bank account.


Let us go through the steps of using the app:

Select the coin for which you want arbitrage trade profit to be calculated.
Select the number of coins according to your trading capacity. The total cost will be displayed below for each exchange.
The app will tell you the best opportunity for trade after comparing all the platforms’ prices and fees.
Now you might be wondering why everyone’s not rich then? The answer to this question is that arbitrage opportunities are scarce. They are extremely rare in some well-known coins like Bitcoin and Ethereum due to the high gas fees they charge. Those who do not understand gas fees consider it as a transaction cost. Also, the fees charged for wallet transfer and withdrawal cut down the profits significantly. We have experienced more opportunities for arbitrage on coins such as Solana and Cardano, which are lesser-known but have promising platforms and logic on which they are built. They charge significantly fewer gas fees for transfer and have recently shown increased demands due to their improvements to well-established cryptocurrencies. The highly volatile market for these cheaper coins results in disparity among the price quotes of different exchanges. They are also proven to have lower transaction times.

One last thing to point out is that cryptocurrency transfer among wallets takes time. The prices might have changed in the meantime, and arbitrage might not always be profitable. Although, considering the opportunities seen in the market, the profit to risk ratio in arbitrage for cryptocurrency is pretty good. Keep looking for profits on our app!

Link to the app:
https://coin-compare-17.herokuapp.com/
