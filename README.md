#### Command to build the docker image ####

docker build -t my-node-app . 

#### Command to run a container using created docker image ####

docker run -p 3000:3000 my-node-app

#### Command to start the container using docker-compose ####

docker-compose up
