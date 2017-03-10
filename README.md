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

Delete all containers: docker rm -f $(docker ps -aq)
Delete all images: docker rmi -f $(docker images -q)
Delete dangling images: docker rmi $(docker images -q -f dangling=true)



## docker-compose build
## docker-compose up -d

## docker-compose run web bin/rails db:create db:migrate RAILS_ENV=development
## docker-compose run web bin/rails db:migrate
## docker-compose run web bin/rails db:migrate RAILS_ENV=development


# console os
## docker run -i -t 7587587
