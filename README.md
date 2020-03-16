## Getting started

#1.- Create a yml file with the services you want to compose

#1.a - Create a ".env" file which will supply the postgres environmental values

#2 -execute docker-compose to build, start services 

    docker-compose -f PostGres_PGAdmin4.yml up

#3 - To determine host name (to connect from PGAdmin), inspect the postgres container

    docker inspect docker_postgres


## Maintenance Commands after build

#1 - docker-compose -f <yml file> start
#2 - docker-compose -f <yml file> stop

## Clean up commands

#1 - docker system prune -a

