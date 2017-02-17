# docker-basic-command

##Delete all containers
docker rm $(docker ps -a -q)
##Delete all images
docker rmi $(docker images -q)

#!/bin/bash
# Delete all containers
docker rm $(docker ps -a -q)
# Delete all images
docker rmi $(docker images -q)
