Build docker
`docker build -t node-docker .`

Check images
`docker images`

Run docker
`docker run -it -p 9000:3000 node-docker`

Run docker in detached mode in background
`docker run -d -p 9000:3000 node-docker`

Check running processes
`docker ps`

Stop and remove docker process
`docker rm -f <container id>`
