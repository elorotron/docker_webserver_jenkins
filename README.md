# Dockerfile
### docker build -t name_of_image:version /path/to/dockerfile
## Network
### docker network create <name_of_network>
## For apache image
### docker run -d -p 8090:8090 --network <name_of_network> --name name_of_container name_of_image:version
## For nginx image
### docker run -d -p 80:80 -p 443:443 -v directory/to/get/logs:/volume --network <name_of_network> --name name_of_container name_of_image:version


# Docker compose
## Start compose
### docker compose -f ./docker-compose.yml up -d
## Down compose
### docker compose -f ./docker-compose.yml up -d


#test
