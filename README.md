# netcore-docker
sample creating docker image for dotnet core project

## how to build image
run `docker build -t docker-api`

## how to run image
run `docker run --name docker-api -p 8080:80 docker-api`

## how to test
go to `localhost:8080/api/values`