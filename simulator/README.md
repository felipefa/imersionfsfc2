# Coordinates Simulator

Given a client and route ids, this Go program simulates each coordinate of the route that will be consumed by the front end.

**Important**: The Apache Kafka app must be executed first.

## Run the app

Execute:

```
docker-compose up -d
# Enter the container and open bash
docker-compose exec app bash
# Run the app
go run main.go
```
