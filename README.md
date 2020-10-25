# Java RabbitMQ (Publisher/Consumer)

**How to run RabbitMQ:**

- Execute RabbitMQ with Docker:
```
docker run -d --hostname my-rabbit --name some-rabbit -p 8080:15672 -p 5672:5672 rabbitmq:3-management
```
- Execute RabbitMQ with docker compose:
```
docker-compose up -d
```

- RabbitMQ management:
    - http://localhost:8080
    - user/pass (default admin/admin)
