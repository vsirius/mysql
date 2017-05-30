# mysql
```
docker run -p 3306:3306 --name application-db -e  MYSQL_USER="app" \
-e MYSQL_PASSWORD="Ws0823~LL" \
-e MYSQL_DATABASE="application" \
-e  MYSQL_RANDOM_ROOT_PASSWORD="yes" \
-v ./sql:/docker-entrypoint-initdb.d \
-d siriusgti/mysql-db 
