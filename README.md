# Kapua Deployment

## How to run
```
docker-compose up
```

## Links

### Kapua Console
```
http://localhost:8080
```

### Swagger
```
http://localhost:8081
```

### Grafana
```
http://localhost:3000
```

## Issues
Kura simulator may fail because of mqtt broker didn't start. You must restart it.
```
docker restart kapua-deployment_kura-simulator_1
```
