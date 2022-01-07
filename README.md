# GoChain

API to interact with Ethereum Blockchain using Go.

## Make a transaction

curl -d '{"privKey":"2cbacc25c50e2152269134c89a2fee1a8c9319c54c5e04d916b2ad28a747c2c0", "to":"0xff55e2F88ADAD77c816cED54b8D342988d889e01", "amount":1000000000000000000}' -H "Content-Type: application/json" -X POST http://localhost:8080/api/v1/eth/send-eth

## View TX

http://localhost:8080/api/v1/eth/get-tx?hash=0xf36cbdb849ee3865c99e5b536529a99f23fcf820f1c81b548bb4c79dcac31de8

## View Balance

http://localhost:8080/api/v1/eth/get-balance?address=0xff55e2F88ADAD77c816cED54b8D342988d889e01

## View Last Block

http://localhost:8080/api/v1/eth/latest-block
