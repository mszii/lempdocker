::validate config
docker-compose config -q

::build image and container with docker-compose
docker-compose up -d


docker container ls -a 
docker container prune

docker system prune