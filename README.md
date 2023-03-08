https://tech-diary.net/how-to-create-postgresql-container/

start docker

-   `docker-compose up -d`
-   `docker-compose ps`
-   `docker container exec -it mypg bash`
-   `psql -p 5432 -U admin -d test_db`
-   `\l`

exit from psql

-   `exit`
-   `docker-compose stop`

delete container

-   `docker-compose down`
