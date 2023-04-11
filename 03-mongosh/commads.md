## Connect to container

docker-compose exec mongodb bash

## Connect with mongosh

mongosh "mongodb://root:root@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://VicFlores11:monoloco69@mongodbintro.stbsn8q.mongodb.net/test"

## Example queries

show dbs

show collections

use("platzi_store")
db.Products.find()
