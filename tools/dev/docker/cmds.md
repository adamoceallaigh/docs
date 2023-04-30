# Documentation: Commands

`docker exec -it ? bash|sh`: Execute bash shell on the docker container specified by ?

`docker ps`: Lists the docker containers downloaded on the daemon

`docker ps -a`: Lists the running docker containers downloaded on the daemon

`docker inspect ?`: inspects the currently selected docker element by docker id|name specified by ?

`docker logs ?`: outputs the logs of the docker container specified by ?

`docker network list|docker network ls`: lists the docker networks set up on your machine

`docker stop $(docker ps -aq)`: stops all running docker containers

`docker rm $(docker ps -aq)`: removes all docker containers

`docker compose up`: starts a docker network from the docker-compose file located at the current working directory

`docker compose down`: shuts down a docker network from the docker-compose file located at the current working directory

`docker rmi $(docker images -q)`: removes all docker images located on the machine

`docker build . -t ?`: builds a docker image locally from the Dockerfile located at the current working directory, naming the image ?

`docker search ?`: searches for image on the Docker hub, where ? is the name of the image

`docker version`: outputs the current version of docker installed on the machine

`docker kill ?`: shuts down a docker container, where ? is the name|id of the container

`docker cp ?:{Docker-file-path} {computer-file-path}`: copies a file or folder from the docker container file system to the machines filesystem

eg. `docker cp ?:/usr/local/apache2/logs/httpd.pid /home/greatlearning/`

`docker volume create`: creates a volume so that the docker container can use it to store data

`docker volume ls`: lists all volumes on the daemon
