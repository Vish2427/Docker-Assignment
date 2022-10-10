1. Pull

Command used to pull image from the Docker Hub repo
```
docker pull <repo_name>
![pull](https://user-images.githubusercontent.com/98541876/194858662-0a10819d-fb73-41e6-a503-afad8af7b914.png)

```
2. Build Image

Command use to build image
```
docker build -t <repo_user_name>/<image_name> .

```
3. List Images

Command used to list local images
```
docker images
```

4. Run image

Command used to run docker image locally
```
docker run -p <local_port_number>:<host_port> <image_name>

```
5. Push image to Docker Hub repo

Command to push image to Docker Hub repo
```
docker push <user_name>/<image_name>:<tag>
```
6. Start Conatiner

Command to start existing conatiner 
```
docker start <conatiner-id>
```

7. Conatiner Stop

Command to stop running conatiner
```
docker stop <conatiner-id>
```

8. Conatiner force stop

Command to force stop the crunning conatiner

```
docker kill <conatiner-id>
```

9. Delete existing conatiner

Command to delete exisiting conatiner

```
docker rm <conatiner-id>

```
10. Delete image

Command to delete existing image in local

```
docker rmi <image_name>
```

11. List of running conatiners

Command use to list the local running conatiners
```
docker ps
```
12. Entering running conatiner

Command used to enter into running container
```
docker exec -t <container-id> bash
```
13. Logs

Command use to check logs of running conatiner
```
docker logs <container-id> -f
```
14. Create volume

Command use to create volume
```
docker volume create <volume_name>
```
15. List volumes
Command used to list all volumes
```
docker volume ls
```

