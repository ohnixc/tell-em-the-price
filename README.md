# Tell Em the Price

```
git clone https://github.com/ohnixc/crypto-fetcher.git
cd crypto-fetcher
eg python crypto-fetcher.py [COIN1] [COIN2] [DURATION=minute(m)hourly(h)daily(d)] [TICKSIZE=1,3,5,10,60] [QUANTITTY=number<100]
python crypto-fetcher.py BTC USDT m 10 20
output => logfile containing the last 20 BTC/USDT pair prices in 10 minute increments
```
