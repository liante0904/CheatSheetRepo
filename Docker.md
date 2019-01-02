# Docker CheatSheet
## Docker install
[install Docker for Mac in Docker.com](https://docs.docker.com/docker-for-mac/install)

## Docker commend

### check version, info
`$ docker --version`  
`$ docker info`  

### docker run
`$ docker run hello-world`  
`$ docker image ls`  
`$ docker container ls --all`  


## Remove Image 
`$ docker rmi $image_ID`

## Remove Container 
`$ docker rm $container_ID`

## docker Command to Container 
`$ docker exec -it  $container_ID /bin/bash`

