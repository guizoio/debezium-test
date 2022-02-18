# debezium-test
estudo sobre o debezium e postgres

## Exutando projeto

```
docker-compose up -d
```
## Criando curl

```
curl -i -X POST -H "Accept:application/json" -H "Content-Type:application/json" 127.0.0.1:8083/connectors/ --data "@debezium.json"
```

