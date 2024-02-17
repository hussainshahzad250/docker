## Create docker images from docker container and push to docker hub

docker commit <container_id> your-docker-hub-username/your-image-name:tag

```
docker commit 90bb807b5928 husssainshahzad/jenkins:1.0
```

```
docker login
```

```
docker push husssainshahzad/jenkins:1.0
```
