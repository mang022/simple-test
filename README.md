# Simple Back-end Test

## Build and Run main.go

```
go mod tidy

go build

./simple-test
```

Test call `localhost:8080/ping` using curl, PostMan, and so on.

## Find exchange rate

0. Implement a simple Restful API server.


1. Return a current exchange rate of KRW (Won).

Path
```
[GET] /exchange/:code
```
{:code} is a path parameter.

For example, if you want to get a current Dollar(USD) to Won(KRW) exchange rate, the code is USD.

If the code is JYP, return a current JYP to KRW exchange rate.

   
Response (JSON)
```
{
   "rate": 1400.00   // to two decimal places
}
```



## Caution
- The time limit is 40 minutes.
- You can search for it, but please show me the screen you search for.
- https://freecurrencyapi.com
- API KEY: fca_live_FtBXLKYTjmeVMXrF7tpU9SpxD5OoEQKSGffFC2y7
