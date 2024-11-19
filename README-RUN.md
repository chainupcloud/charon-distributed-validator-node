# Run
```
# modify .env
CHARON_BEACON_NODE_ENDPOINTS=
```

```shell
docker compose down
docker compose up -d
docker compose logs --tail 300 -f charon lodestar
docker compose logs charon lodestar
```