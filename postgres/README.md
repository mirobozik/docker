# PostgreSQL with pgAdmin

docker compose for postgresql and pgadmin tool

## Prerequisities

- docker or podman installed
- docker compose or podman-compose installed
- `dev` network created

## Dry Run

```bash
docker compose -f ./docker-compose.yml --env-file ./.env up --dry-run
```

## Run (up)

```bash
docker compose -f ./docker-compose.yml --env-file ./.env up -d
```

## Delete

deletes containers

```bash
docker compose down
```

deletes containers with volumes

```bash
docker compose down -v
```

## Start / Stop

```bash
docker compose start
```

```bash
docker compose stop
```
