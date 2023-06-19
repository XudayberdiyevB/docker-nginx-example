## Commands

1. `docker build -t my-nginx:v1 .` - build docker image with Dockerfile
2. `docker images` - show built docker image
3. `docker run -d -p 80:80 my-nginx:v1` - run docker container with **my-nginx** image and **80** port
4. `docker container ls` - show running container
5. `docker stop <CONTAINER_ID>` - stop docker container with ID

For testing enter http://localhost:80