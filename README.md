#Install the docker and the docker compose
- you can install the docker and docker compose by:
curl, apt, or yum

#test the docker
test the docker run, you can run docker run hello-world

#create docker-compose.yml
- this file contain configuration of install wordpress

#deploy the compose.yml
- run docker-compose up -d

#deploy scalable wordpress
if you need scalable, deploy this compose to another server:
1. install pre-requisites like docker and docker-compose
2. clone the git
3. run docker-compose up -d
