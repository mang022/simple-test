# Simple Back-end Test

## Build and Run main.go

```
go mod tidy

go build

./simple-test
```

Test call `localhost:8080/ping` using curl, PostMan, and so on.

## Recover panic in a custom way
1. Create a new endpoint ([GET] /panic).
2. Force to generate a panic like nil pointer error when you request /panic. Do not use panic() function.
3. When a panic occurs, return http status OK and JSON message {"error": "panic recovered"}.

## Fill running_total_quantity
Run simple.sql.

Fill running_total_quantity per item using SQL query.

## Caution
- The time limit is 40 minutes.
- You can search for it, but please show me the screen you search for.
