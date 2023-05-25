# REST API 

## BUILD
````
docker-compose up -d db
docker-compose logs db
docker compose build
docker compose up -d rustapp
docker container ps -a


docker exec -it db psql -U postgres
\dt
select * from users;
````

Inspired: https://dev.to/francescoxx/rust-crud-rest-api-3n45

