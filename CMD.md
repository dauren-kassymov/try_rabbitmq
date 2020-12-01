http://prntscr.com/vtatqk

```
docker network create rabbits

docker run -d --rm --net rabbits -p 8080:15672 --hostname rabbit-1 --name rabbit-1 -e RABBITMQ_DEFAULT_USER=quest -e RABBITMQ_DEFAULT_PASS=quest rabbitmq:3.8
```