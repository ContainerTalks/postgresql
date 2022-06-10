# Postgres

## Dump Schema + Data

```bash
docker exec -i postgres_postgresql_1 /bin/bash -c "pg_dump -U <USERNAME> <Database>" > dump.sql
```

## Dump Only Schema: 

```
docker exec -i postgres_postgresql_1 /bin/bash -c "pg_dump -U <USERNAME> -s <Database>" > dump.sql
```
