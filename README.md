# dockertraining

https://github.com/oudivad/dockertraining
Create Dockerfile

Create the Docker Image
docker build -t mywebsite:v1 .

Run the container
docker run -d -p 80:80 mywebsite:v1

Create the dockercompose
docker-compose.yaml

Run the docker-compose.yaml
docker-compose up -d

Website is reachable from port 80
Cadvisor from 9000
