## Instruction
To use public API you need to type simply requests: 

```
https://beatcoin.pl/public/graphs/FirstcurrencySecondcurrency/periodoftime.json
```

For example: 

```

https://beatcoin.pl/public/graphs/BTCLTC/1day.json
```


## Available values

### First currency

```
BTC
PLN
USD
EUR
```


### Second currency

```
BTC
LTC
ETH
ETC
DASH
DOGE
BCN
ZEC
```


** You can not use BTCBTC pair. **

### Time periods

```
15min
1day
7days
1mounth
```


## Ticker

To use ticker just call 

```
https://coinbe.net/public/graphs/ticker/ticker.json```


Ticker file shows you array of actual status of beatcoin markets.

## Responses

Server will give you response with 70 positions of chosen parameters. 


```
{"time":1499628480,"open":"9680.30000000","high":"9680.30000000","low":"9680.30000000","close":"9680.30000000","vol":"1.50000000"},
{"time":1499629440,"open":"10000.00000000","high":"10000.00000000","low":"10000.00000000","close":"10000.00000000","vol":"2.70000000"},
{"time":1499630400,"open":"10000.00000000","high":"10000.00000000","low":"10000.00000000","close":"10000.00000000","vol":"0.00000000"}]
```

```
Outputs:
time - time in timestamp
open -  first offer in a period of time
high - highest offer in a period of time
low - lowest offer in a period of time
close - last offer in a period of time
vol - volumen in a period of time
```



