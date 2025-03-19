### Redis docker for Egress Server (for local development)

Goto redis.conf for configuration
```bash
~/redis/redis.conf
```
To start the container:
```bash
docker-compose up -d
```

password: `mypassword`
port: `6379`


To see all the running containers:

```bash
docker ps
```

To get a shell into the container:

```bash
docker exec -it redis sh
```

To open the redis cli:

```bash
redis-cli
```

keys:

```bash
keys *
```

Auth:

```bash
auth mypassword
```

To get variable values:

```bash
config get *
```
example:

```bash
config get protected-mode
```











