# cryptoflux-docker-compose
docker compose for cryptoflux

## How To Use
After docker build of [cryptoflux](https://github.com/hill-daniel/cryptoflux), use docker-compose up to start service.

## Required env
* INFLUX_HOST - the influxdb host name
* INFLUX_USER - the influxdb username
* INFLUX_DB_NAME - name of the database
* INFLUX_PW - the provided password
* TICKER_ENDPOINT - URL of the endpoint for retrieving quotes
* TICKER_API_KEY - the API key for authenticating
* LOG_LEVEL - the log level
* POLL_INTERVAL - the poll interval in minutes
