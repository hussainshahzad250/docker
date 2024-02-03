## Create docker images from docker container and push to docker hub

docker commit <container_id> your-docker-hub-username/your-image-name:tag

1.	docker commit 90bb807b5928 husssainshahzad/jenkins:1.0
2.	docker login
3.	docker push husssainshahzad/jenkins:1.0
