```
docker build . -t dnka/rabbitmq-publisher:v1.0.0
docker run -it --rm --net rabbits -e RABBIT_HOST=rabbit-1 -e RABBIT_PORT=5672 -e RABBIT_USERNAME=quest -e RABBIT_PASSWORD=quest -p 80:80 dnka/rabbitmq-publisher:v1.0.0
```