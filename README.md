# DynamoDB Local in Docker

About Docker Local: [Setting Up DynamoDB Local (Downloadable Version)](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.html)

## Usage
### In-Memory mode

```
docker run -p 8000:8000 lulichn:dynamodb-local
```

### Use options

See `-help`

```
docker run -p 8000:8000 lulichn:dynamodb-local -help
```

### Notice
`-dbPath` not work

## Build

```
docker build -t <TAG> .
```
