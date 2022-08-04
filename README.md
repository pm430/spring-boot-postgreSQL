### docker

1. docker run -p 5432:5432 -e POSTGRES_PASSWORD=pass -e POSTGRES_USER=pm430 -e POSTGRES_DB=springboot --name postgres_boot -d postgres
2. docker exec -i -t postgres_boot bash
3. psql --username=pm430 --dbname=springboot

### postgreSQL

1. springboot=# \dt
2. select * from USERS;