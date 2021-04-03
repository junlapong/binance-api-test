# Binance API Spot Trading

## Prerequisites

1. Open [https://testnet.binance.vision](https://testnet.binance.vision/) and log in with a GitHub account.
2. Under API Keys, Click on Generate HMAC_SHA256 Key to create a pair (the __API Key__ and the __Secret Key__).

## Testing

### Postman

Use Postman collections from [github.com/binance/binance-api-postman](https://github.com/binance/binance-api-postman)

```
gh repo clone binance/binance-api-postman
```

### HTTP Request

see [request.http](request.http)

### Go

```
go run main.go | jq
```

## Reading List

- [ ] [A Complete Guide to Cryptocurrency Trading for Beginners](https://academy.binance.com/en/articles/a-complete-guide-to-cryptocurrency-trading-for-beginners)
- [ ] [Binance API Series Pt. I – Spot Trading with Postman](https://academy.binance.com/en/articles/binance-api-series-pt-1-spot-trading-with-postman)
