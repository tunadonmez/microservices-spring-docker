# Docker

## Images

- https://hub.docker.com/u/tunadonmez
- Eureka
	- tunadonmez/microservices-naming-server:0.0.1-SNAPSHOT
- API GATEWAY
	- tunadonmez/microservices-api-gateway:0.0.1-SNAPSHOT

## URLS

#### Currency Exchange Service
- http://localhost:8000/currency-exchange/from/USD/to/TRY

#### Currency Conversion Service
- http://localhost:8100/currency-conversion/from/USD/to/TRY/quantity/10
- http://localhost:8100/currency-conversion-feign/from/USD/to/TRY/quantity/10

#### Eureka
- http://localhost:8761/

#### Zipkin
- http://localhost:9411/

#### API GATEWAY
- http://localhost:8765/currency-exchange/from/USD/to/TRY
- http://localhost:8765/currency-conversion/from/USD/to/TRY/quantity/10
- http://localhost:8765/currency-conversion-feign/from/USD/to/TRY/quantity/10
- http://localhost:8765/currency-conversion-new/from/USD/to/TRY/quantity/10

#### Commands
```
docker-compose up
docker-compose down
```