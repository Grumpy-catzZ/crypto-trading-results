# crypto-trading-results

Following are results from a recently developed quantitative trading strategy.
Asset traded- BTCUSDT. Data used- daily OHLC from 2018 to 2023.

I am working on it to further minimize the drawdowns. 

### Strategy Summary ( 2018 - 2023 )

![summary](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/4e502113-c1c3-4aba-8034-12c48ef332aa)


## Static Backtesting
Each trade is taken with a fixed amount. In this case its 1000

| Parameter               | Value                            |
|-------------------------|----------------------------------|
| From                    | 2018-04-08 5:30:00               |
| To                      | 2024-01-01 5:30:00               |
| Total Trades            | 173                              |
| Winning Trades          | 98                               |
| Losing Trades           | 75                               |
| No. of Long Trades      | 173                              |
| No. of Short Trades     | 0                                |
| Win Rate                | 56.65                            |
| Gross Profit            | 5016.323570006483                |
| Net Profit              | 4756.823570006483                |
| Average Profit          | 27.496090000037476               |
| Maximum Drawdown(%)     | 16.472494216937626               |
| Average Drawdown(%)     | 2.496123682078203                |
| Largest Win             | 914.6532809143577                |
| Average Win             | 79.50551393887427                |
| Largest Loss            | -111.05662446634955              |
| Average Loss            | -38.88435897453053               |
| Maximum Holding Time    | 52 days 00:00:00                 |
| Average Holding Time    | 5 days 10:57:34.335260115        |
| Maximum Dip             | 21.64276632640592                |
| Avg. Dip                | 3.453915840516478                |
| Sharpe Ratio            | 4.650345391512141                |
| Sortino Ratio           | 17.909194024331814               |

## Compounded Backtesting 
PnL realized after a trade is invested back into the market.

| Parameter                    | Value                       |
|------------------------------|-----------------------------|
| Initial Balance              | 1000                        |
| Number of Trades             | 173                         |
| Maximum Drawdown             | -26.903208189242044         |
| Maximum PNL                  | 8678.544237402244           |
| Minimum PNL                  | -2824.1202112591805         |
| Max Portfolio Balance        | 43638.874850490894          |
| Minimum Portfolio Balance    | 952.7374760384477           |
| Final Balance                | 43456.70908105328           |
| Total Fee                    | 3899.9128953246473          |
| Buy and Hold Returns         | 5295.18                     |  

### Close vs PnL

![pnl](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/4ee21789-dbe9-46aa-b419-6f11c227b8f4)


### Monthly Returns

![monthly](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/7cdf0a73-2787-4d78-a746-4a92108d1c13)


### Yearly returns with signals

![2018](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/b25e1492-1423-46d7-95a1-8c3a9b3b2343)
![2019](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/84e4a957-26bc-42cc-8114-25a31d61a9f5)
![2020](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/a76a68fe-a3a5-477f-9921-fa7d021506ac)
![2021](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/4b77d4cd-fe01-43c0-8dc3-cb03a0242552)
![2022](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/4a162823-9b94-458c-a826-1ed806895351)
![2023](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/0c947c89-6390-47a0-b034-7d24c5eef7b0)


