### Docker Notes:
- download the image
- 

<!-- you must use sudo for linux -->


Some helpful commands for docker:
```
docker run <imagename>      ==> check if it exists, if not download it
docker run hello-world

docker ps -all              ==> see all images
docker images   
docker container ls -a      ==> see all containers  

docker container rm <containerID>    ==> remove a container
docker image rm <imagename or ID>    ==> remove an image




docker image ls            ==> list of local images


docker container ls                 ==> list of running containers
docker container run redis          ==> run redis image
docker container run -d redis       ==> run image in background (-d Detached)
docker container run redis:alpine   ==> tag alpine

docker inspect <imagename>          ==> information about image
docker inspect redis:latest
docker inspect redis:alpine


docker info
docker logs <containerID or name>   ==> info about container
docker stats <containerID or name>

```



<!-- https://www.freecodecamp.org/news/github-flavored-markdown-syntax-examples/ -->