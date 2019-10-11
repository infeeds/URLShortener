# Infeeds URL Shortener API

Use HTTP GET or REST API to get shortened URL. Retreived data will be encoded in JSON.

## Request
```
https://infd.in/api/short?url=https://infeeds.com
```

## Output
#### Success
```
{"status":1,"message":"URL is shortened","url":"https:\/\/infeeds.com","id":"22D28","short":"https:\/\/infd.in\/22D28","hits":"7","time":"2 years ago"}
```

#### Failure
```
{"status":0,"message":"Your monthly usage quota is full, visit your infeeds account to fix this issue","url":"https:\/\/infeeds.com\/account\/apis"}
```
