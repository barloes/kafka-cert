# starting

## starting up kafka
```
docker compose up
```

## open terminal 1(producer)
``` 
kafka-console-producer --topic test --bootstrap-server localhost:9092
```

## open terminal 2(consumer)
```
kafka-console-consumer --topic test --bootstrap-server localhost:9092
```