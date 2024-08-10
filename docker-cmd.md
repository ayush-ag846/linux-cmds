### 1. To get the IP of docker container running in linux machine
```
docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAdress}}{{end}}' <container_name/id>
```

### 2. List all docker container ids, either run/stop
```
docker ps -a -q
```
