
## Commands
- build and start container
```docker
docker-compose up -d
```

- stop and remove containers
```docker
docker-compose down -v
```
- list containers
```docker
docker ps
```

- kill all containers
```docker
docker kill $(docker ps -q)
```

- access to container
```docker
docker exec -it CONTAINER_ID bash
```
