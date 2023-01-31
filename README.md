# nodejs-docker-compose.

## 2. Tooling.

### 2.4 Setup Developer local env with Docker Compose.

#### Task.

Create docker compose file that will include the LTS version with Postgres, RabbitMQ and Redis. All services should run on the same network and be exposed on the default port. Use environment variables for configuring docker containers.

There is approved list of environment variables:
```
DB_URL=postgresql://postgres:password@localhost:5432/nodejs-db
CACHE_URL=redis://localhost:6379
BUS_URL=amqp://user:pass@localhost:5672
```
