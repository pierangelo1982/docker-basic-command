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



## docker-compose build
## docker-compose up -d

## docker-compose run web bin/rails db:create db:migrate RAILS_ENV=development
## docker-compose run web bin/rails db:migrate
## docker-compose run web bin/rails db:migrate RAILS_ENV=development
