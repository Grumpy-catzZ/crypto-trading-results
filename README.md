# crypto-trading-results

Following are results from a recently developed quantitative trading strategy.
Asset traded- BTCUSDT. Data used- daily OHLC from 2018 to 2023.

I am working on it to further minimize the drawdowns. 

### Strategy Summary ( 2018 - 2023 )

![summary](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/678b8e94-c166-4f79-8c42-8d3d4fade1d9)


## Static Backtesting
Each trade is taken with a fixed amount. In this case its 1000

| Parameter               | Value                            |
|-------------------------|----------------------------------|
| From                    | 2018-01-08 5:30:00               |
| To                      | 2024-12-31 5:30:00               |
| Total Trades            | 128                              |
| Winning Trades          | 76                               |
| Losing Trades           | 52                               |
| No. of Long Trades      | 124                              |
| No. of Short Trades     | 0                                |
| Benchmark Return(%)     | 11.003895980148354               |
| Win Rate                | 59.38                            |
| Gross Profit            | 5303.286367164537                |
| Net Profit              | 5111.286367164537                |
| Average Profit          | 39.93192474347295                |
| Maximum Drawdown(%)     | 20.790708505684297               |
| Average Drawdown(%)     | 2.2861724896457147               |
| Largest Win             | 989.0097052182377                |
| Average Win             | 96.1145781743257                 |
| Largest Loss            | -111.05662446634955              |
| Average Loss            | -37.05911884695491               |
| Maximum Holding Time    | 90 days 00:00:00                 |
| Average Holding Time    | 5 days 08:48:45                  |
| Maximum Dip             | 21.64276632640592                |
| Avg. Dip                | 3.395589860471221                |
| Sharpe Ratio            | 5.204325570293299                |
| Sortino Ratio           | 25.752076688191483               |

## Compounded Backtesting 
PnL realized after a trade is invested back into the market.

| Parameter                    | Value                       |
|------------------------------|-----------------------------|
| Initial Balance              | 1000                        |
| Number of Trades             | 128                         |
| Maximum Drawdown             | -22.7875153142199           |
| Maximum PNL                  | 18849.986400225076          |
| Minimum PNL                  | -4714.273809317022          |
| Max Portfolio Balance        | 56627.65517760759           |
| Minimum Portfolio Balance    | 936.9271178832888           |
| Final Balance                | 54606.410743784705          |
| Total Fee                    | 3847.73458854482            |
| Buy and Hold Final Balance   | 851.62                      |  

### Close vs PnL

![close v pnl](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/5c4de19d-2734-45a0-8440-e4a1100b1f41)

### Monthly Returns
Initially, first 3 months data is used for training. After that walk-forward optimization method is used to train and predict.

![d7b726bd-0f42-4797-a8f2-00baacc24823](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/1e7e87fe-f193-474d-b401-cf6d7651264d)

### Yearly returns with signals

![280cf385-ae2f-46b8-b8ca-86b91ebbb3e7](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/19939940-752a-4c20-ac13-c26fea2c5482)

![93a29489-fd32-4c0a-8ca7-5b2ce8313903](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/3d2a5db5-804b-4c78-93dc-55871dae80f4)

![8d7520e8-bf86-4031-9ba1-5963026c1922](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/0a3bfded-6768-419d-b4e0-8b1c030b741e)

![ab76449a-facb-4d7a-924e-68f56448df64](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/3f9d8630-855e-42df-9fbb-b01cb5d12192)

![34249a05-6bd9-482c-bd52-1f439c6de10d](https://github.com/Grumpy-catzZ/crypto-trading-results/assets/44294632/8ae4d918-9942-4cbd-bdce-bece76c95e2c)




