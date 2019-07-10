# Start it
docker-compose up -d

# test 
docker exec -it mongo bash

mongo -u admin -p passw0rd --authenticationDatabase admin data
show dbs
show collections