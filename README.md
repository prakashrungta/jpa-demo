# demo-jpa

This Application creates a table called users and creates a spriing boot demo application and binds with postgresql data base

# Refer this to setup the Swagger 
https://medium.com/@ByteCodeBlogger/springboot-3-and-springdoc-openapi-3-swagger-impl-no-operation-defined-in-spec-error-f18f70f8ddf6

#Launch the Swagger with this UI  http://localhost:8080/swagger-ui/index.html

# Refer this to setup the Postgres in Docker 
https://medium.com/@marvinjungre/get-postgresql-and-pgadmin-4-up-and-running-with-docker-4a8d81048aea

docker pull postgres

docker pull dpage/pgadmin4

docker run --name postgrestutorial -e POSTGRES_PASSWORD=password -p 5432:5432 -d postgres

docker ps

docker run --name pgadmin-container -p 5050:80 -e PGADMIN_DEFAULT_EMAIL=abc@gmail.com -e PGADMIN_DEFAUL

docker exec -it postgrestutorial sh

# cat /etc/hosts  [ To get the IP Address ]
172.17.0.2      9a22aa96d7d3

