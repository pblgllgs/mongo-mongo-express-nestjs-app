# Init

## Env variables

Rename file __.env.example__ to __.env__ and complete de fields:

```$bash
MONGO_USERNAME=
MONGO_PASSWORD=
MONGO_DB_SERVER_NAME=
```

## Docker compose stack

```$bash
docker compose up -d
```

## Seed aand fetch data

### Seed

```$bash
http://localhost:3000/api/v2/seed
```

### Fetch data

```$bash
http://localhost:3000/api/v2/pokemon?limit=20&offset=40
```
