# asi nos conectamos a un servicio que tengamos con monog

```sh
docker-compose exec mongodb bash
```

# conexion con mongosh

```sh
# dentro de las comillas va la url de conexion ya sea de atlas y si estas en local seria del local, puede ser cuallquiera de las dos
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://jhonatanech2002:n6DDb7jDqG62Zgiq@cluster0.fkfezed.mongodb.net/"
```


```sh
# ver las bases de datos que tiene el clouster de información
show dbs

show collections
```
