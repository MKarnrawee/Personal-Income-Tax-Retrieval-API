# Personal-Income-Tax-Retrieval

## Installation
```shell
# Clone project
$ git clone https://github.com/MKarnrawee/Personal-Income-Tax-Retrieval.git
$ cd tax-calculation

# Install dependencies
$ npm install
```

## Pre-Requisites
* git
* Node.js v12.22.x

## Run code locally
```shell
$ node index.js
```

## cUrl for testing
```shell
$ curl --location --request GET 'localhost:8000/getpit' \
--header 'Content-Type: application/json' \
--data-raw '{
    "netIncome": 5000000
}'
```
