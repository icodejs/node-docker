# node-docker
Docker experimentation

[Getting Started](https://nodejs.org/en/docs/guides/nodejs-docker-webapp/)

## Install Docker
[Docker](https://docs.docker.com/docker-for-mac/)

## Create app
Git clone repo and cd into root directory

## Building your image
`$ docker build -t <your docker username>/node-web-app .`

## List Docker images
`$ docker images`

## Run the image
`$ docker run -p 49160:8080 -d <your docker username>/node-web-app`

## Print the output of your app:

### Get container ID
`$ docker ps`

### Print app output
`$ docker logs <container id>`

## Enter the container
`$ docker exec -it <container id> /bin/bash`

## Stop image
`$ docker stop <container id>`
