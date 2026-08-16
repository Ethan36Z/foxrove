# FoxRove local Docker deployment

FoxRove is a static Nginx site bound only to <http://127.0.0.1:8082>.

## Build and start

```bash
docker compose up -d --build
```

## Stop

```bash
docker compose down
```

## Status and logs

```bash
docker compose ps
docker compose logs --tail=100 frontend
```
