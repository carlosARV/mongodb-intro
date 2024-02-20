# Connect to the container
```sh
docker-compose exec mongodb bash 
```

# Connect with mongosh
```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
mongosh "mongodb+srv://mondongo_platzi:kgTD6Bc84suaGQmQ@atlascluster.wnbtjd2.mongodb.net/"
```

# Commands to run
```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.productus.find().pretty(true)
```