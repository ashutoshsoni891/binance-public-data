# Binance Scraped Data
 all Kline, Trade, and AggTrade data for all pairs, month by month, online.


## What data is available

### SPOT

* `AggTrades`
* `Klines`
* `Trades`


#### AggTrades

|Aggregate tradeId|Price|Quantity|First tradeId|Last tradeId|Timestamp|Was the buyer the maker|Was the trade the best price match|
| -- | -- | -- | -- | -- | -- | -- | -- |
|0|0.20000000|50.00000000|0|0|1608872400000|False|True|

#### Klines

|Open time|Open|High|Low|Close|Volume|Close time|Quote asset volume|Number of trades|Taker buy base asset volume|Taker buy quote asset volume|Ignore|
| -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
|1601510340000|4.15070000|4.15870000|4.15060000|4.15540000|539.23000000|1601510399999|2240.39860900|13|401.82000000|1669.98121300|0|

#### Trades

|trade Id| price| qty|quoteQty|time|isBuyerMaker|isBestMatch|
| -- | -- | -- | -- | -- | -- | -- |
|51175358|17.80180000|5.69000000|101.29224200|1583709433583|True|True|



### FUTURES
* USD-M Futures
* COIN-M Futures

#### AggTrades

|Aggregate tradeId|Price|Quantity|First tradeId|Last tradeId|Timestamp|Was the buyer the maker|
| -- | -- | -- | -- | -- | -- | -- |
|26129|0.01633102|4.70443515|27781|27781|1498793709153|true|

#### Klines

USD-M Futures

|Open time|Open|High|Low|Close|Volume|Close time|Quote asset volume|Number of trades|Taker buy base asset volume|Taker buy quote asset volume|Ignore|
| -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
|1499040000000|0.01634790|0.80000000|0.01575800|0.01577100|148976.11427815|1499644799999|2434.19055334|308|1756.87402397|28.46694368|17928899.62484339|

COIN-M Futures

|Open time|Open|High|Low|Close|Volume|Close time|Base asset volume|Number of trades|Taker buy volume|Taker buy base asset volume|Ignore|
| -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
|1591258320000|9640.7|9642.4|9640.6|9642.0|206|1591258379999|2.13660389|48|119|1.23424865|0|

#### Trades

USD-M Futures

|trade Id| price| qty|quoteQty|time|isBuyerMaker|
| -- | -- | -- | -- | -- | -- |
|28457|4.00000100|12.00000000|48.00|1499865549590|true|

COIN-M Futures

|trade Id| price| qty|baseQty|time|isBuyerMaker|
| -- | -- | -- | -- | -- | -- |
|28457|9635.0|1|0.01037883|1591250192508|true|

#### Intervals

All intervals are supported: 
`1m`, `3m`, `5m`, `15m`, `30m`, `1h`, `2h`, `4h`, `6h`, `8h`, `12h`, `1d`, `3d`, `1w`, `1mo`
- `1mo` is used instead of `1M` to supprt non-case sensitive file systems.

