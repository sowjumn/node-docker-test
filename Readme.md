# Node App to learn Docker

# Build the docker image
`docker build -t node-dc-test .`

## Run the docker container

`docker run -p 3000:3000 node-dc-test`


## Look at the port mappings

`docker ps`

`docker port <container>`