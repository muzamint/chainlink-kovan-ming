# deploy chainlink node
```
cd ~/.chainlink-kovan-ming && docker run -p 6688:6688 -v ~/.chainlink-kovan-ming:/chainlink -d --env-file=.env --link some-postgres smartcontract/chainlink local n -p /chainlink/.secret -a /chainlink/.api
```
