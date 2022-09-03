## Create REST API to interact with Ethereum blockchain using Golang
Use go-ethereum (geth) client library to interact with Ganache test network to get the current block and its transactions, to get the transaction for a given hash, to transfer eth between two addresses, and to get the balance of a given address. Use mux to expose those REST API endpoints.

## Prerequisites
Ganache https://www.trufflesuite.com/ganache?ref=hackernoon.com  

## Run
```bash
go run main.go
```

Use the postman collection  
```text
goeth-restapi.postman_collection.json  
```

to run the APIs.