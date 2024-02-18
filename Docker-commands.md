# Docker Utility Script

This script provides a convenient way to manage Docker images and containers through a set of common commands.

## Prerequisites

- Docker must be installed on your system. If not, you can download and install it from [here](https://www.docker.com/get-started).

## Usage

### To create docker image

```bash
docker build -t <image_name>:<image_version> .
```


### Docker Images

To list all Docker images:

```bash
docker images
```

### Remove Docker Image

To remove a Docker image:

```bash
docker rmi <image_name_or_id>
```

### Docker Containers

To check all running containers:

```bash
docker ps
```

To check all containers (running + stopped):

```bash
docker ps -a
```

### Manage Containers

To stop a running container:

```bash
docker stop <container_name_or_id>
```

To start a stopped container:

```bash
docker start <container_name_or_id>
```

To remove a container:

```bash
docker rm <container_name_or_id>
```

### Container Logs

To check the logs of a container:

```bash
docker logs <container_name_or_id>
```

### To go inside docker container 
```bash
docker exec -it <container_id>  /bin/bash
```

### System Cleanup

To clean all unused images, stopped containers, and cache:

```bash
docker system prune -a
```

## Note

- Replace `<image_name_or_id>` and `<container_name_or_id>` with the actual name or ID of the image/container you want to operate on.

---
