# NodeJS Web App with Docker

## Install and Setup
- stable version of node
- stable version of docker
- clone the repo and run `npm install`

## Usage
- To tag (-t) and build the image: `docker build . -t <your_username>/<appname>`
- To list the image: `docker images`
- To run the image in detached in the background (-d) redirected to a private port (-p): `docker run -p 49160:8080 -d <your_username>/<appname>`
- To get container ID `docker ps -a`
- To print the app output `docker logs <container_id>`
- To test the app `curl -i localhost:49160`