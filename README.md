# docker
Playing with docker, docker-compose, swarn

`docker ps -qa` - list all container IDs 
`docker rm $(docker ps -qa)` - remove all existing containers
`docker rmi $(docker images -q)` - remove all existing images
