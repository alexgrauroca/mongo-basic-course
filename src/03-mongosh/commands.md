## Connect to container

```sh
docker compose exec platzi-mongodb bash
mongosh "{{mongoConnectionString}}"
```

## Connect with mongosh
```sh
docker compose exec platzi-mongodb mongosh "{{mongoConnectionString}}"
```

## Mongo commands
```sh
show dbs
show collections
```

```sh
use platzi_store
db.products.find()
```