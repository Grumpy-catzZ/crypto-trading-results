# crypto-trading-results

This strategy takes bets in both long and short direction. 
Asset traded- BTCUSDT. Data used- daily OHLC from 2018 to 2023.

Furthermore, I am partnering with a trading firm to get it deployed. Currently its deployed on test accounts with a small investment.

### Strategy Summary ( 2018 - 2023 )

![summary](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/f3cbace1-7915-43ff-b774-a2e381f2459f)

## Static Backtesting
Each trade is taken with a fixed amount. In this case its 1000

| Metric | Value |
|---|---|
| From | 2018-01-08 05:30:00 |
| To | 2022-12-31 05:30:00 |
| Total Trades | 193 |
| Winning Trades | 108 |
| Losing Trades | 85 |
| No. of Long Trades | 83 |
| No. of Short Trades | 110 |
| Benchmark Return(%) | 11.0 |
| Benchmark Return(on $1000) | 110.04 |
| Win Rate | 55.96 |
| Gross Profit | 6067.72 |
| Net Profit | 5778.22 |
| Average Profit | 29.94 |
| Maximum Drawdown(%) | 30.22 |
| Average Drawdown(%) | 3.71 |
| Largest Win | 899.14 |
| Average Win | 86.28 |
| Largest Loss | -130.45 |
| Average Loss | -41.65 |
| Maximum Holding Time | 81 days 00:00:00 |
| Average Holding Time | 7 days 09:12:07.461139896 |
| Maximum Adverse Excursion | 21.94 |
| Average Adverse Excursion | 4.6 |
| Sharpe Ratio | 4.97 |
| Sortino Ratio | 17.84 |

## Compounded Backtesting 
PnL realized after a trade is invested back into the market.

| Metric | Value |
|---|---|
| Initial Balance | $1000 |
| Number of Trades | 193 |
| Profit Percentage | 9969.17% |
| Maximum Drawdown | 34.37% |
| Average Drawdown | 8.56% |
| Total Time to Recovery(TTR) | 121.0 days |
| Maximum PNL | $23516.55 |
| Minimum PNL | -$7520.74 |
| Max Portfolio Balance | $100691.65 |
| Minimum Portfolio Balance | $757.38 |
| Final Balance | $100691.65 |
| Total Fee | $6666.34 |


### Close vs PnL

![close vs Pnl](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/8630e846-857f-4439-84db-d2235e3998b2)

### Monthly Returns
Initially, first 3 months data is used for training. After that walk-forward optimization method is used to train and predict.

![monthly](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/b26e5d1e-9a23-4b6d-bb2c-6a9c926295e9)

### Yearly Close vs Pnl ( with signals )

![18](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/e3952ee8-8657-4bfe-afcc-3c07b4e852af)

![19](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/dbcdc1bd-277c-4678-88f5-79b3a1951ad5)

![20](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/d5775a73-3f0b-4c8f-aee0-59dcf36febc2)

![21](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/fb8b2376-36e2-4fe4-b33c-d66b6890061f)

![22](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/684a9267-14a8-41e0-8aee-6321519effa0)



