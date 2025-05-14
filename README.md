# demo-docker-postgres

### Iniciar
```
docker compose up -d
```

### Verificar que la base de datos esté creada en docker

```
docker exec -it mi_postgres psql -U usuario -d mibase
```
