## Docker 
// Start Rancher for Docker to work
// Mac OS - arm architecture - silicon chip
1. export DOCKER_DEFAULT_PLATFORM=linux/amd64
2. docker build --pull --rm -f "Dockerfile" -t grizzly-db-batches:latest "." 

### To persist 
1. docker run -it  grizzly-db-batches:latest 

### To delete container after use 
1. docker run --rm -it  grizzly-db-batches:latest 

### Docker image prune 

// build the docker image
docker build --progress=plain -t appui .   
docker run -d --name appui -p 80:80 appui

### Docker images:
ibmjava:8-sfj
ibmjava:8-alpine
ibmjava:8-sfj-alpine

### Podman 

// build the docker image
podman build --progress=plain -t appui .   
podman run -d --name appui -p 80:80 appui

### Nerd CTL

// build the docker image
nerdctl build --progress=plain -t appui .   
nerdctl run -d --name appui -p 80:80 appui