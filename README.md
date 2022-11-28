# Hackathon API PostGres/redis cache
Spring Boot Mysql Redis REST API Cache example

### Prerequisites
- JDK 1.8
- Maven
- Mysql
- Redis (Using Lettuce)

## Quick Start

```
start MySQL service and create database
```

```
start Redis service
```

### Build
```
mvn clean package
```

### Run
```
java -jar target/spring-mysql-redis.jar
```

##
### Get information about system health, configurations, etc.
```
http://localhost:8091/env
http://localhost:8091/health
http://localhost:8091/info
http://localhost:8091/metrics
```


### Swagger-ui REST API Reference & Test
- http://localhost:8080/swagger-ui.html
- Response Content Type : application/json
