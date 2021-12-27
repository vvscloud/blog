# Docker basics
Notes on learning docker  
### Docker commands
Print docker version
> `docker -v`  

Print all docker images
> `docker images`

Print all running containers  
> `docker ps`  
`docker ps -a`

Start a container
> `docker run ubuntu` | ubuntu is the image name

Stop a container
> `docker stop <container_name>`

Remove a container
> `docker rm <container_name>`

Remove images
> `docker rmi <image-name>`

Pull an image
> `docker pull <image>`

Append a command
> `docker run ubuntu sleep 5`

Execute a command
> `docker exec <container_running_name> cat /etc/hosts`

Attach and Detach [ Running in foreground and background ]
> `docker run kodekloud/simple-webapp`  
`docker run -d kodekloud/simple-webapp`  
`docker attach a043d`

---
Docker compose  

---
Advanced Docker Concepts




