1. Pull

Command used to pull image from the Docker Hub repo
```
docker pull <repo_name>

```
![pull](https://user-images.githubusercontent.com/98541876/194858787-f5cda2e5-3516-45a8-a73b-39f732bd9b64.png)

2. Build Image

Command use to build image
```
docker build -t <repo_user_name>/<image_name> .

```
![image build](https://user-images.githubusercontent.com/98541876/194858828-2ec7f633-b391-45d4-b5d6-f4c443210641.png)


3. List Images

Command used to list local images
```
docker images
```
![list of images](https://user-images.githubusercontent.com/98541876/194858882-7d8f0caa-a5c3-43ef-8e77-944bb4179169.png)

4. Run image

Command used to run docker image locally
```
docker run -p <local_port_number>:<host_port> <image_name>

```
![local run](https://user-images.githubusercontent.com/98541876/194858926-e78fc133-a3d1-4f7b-8937-e9258673e5ed.png)

5. Push image to Docker Hub repo

Command to push image to Docker Hub repo
```
docker push <user_name>/<image_name>:<tag>
```
![push](https://user-images.githubusercontent.com/98541876/194858952-fbad5ab7-0b88-439e-a891-571a4818e3ca.png)


6. Start Conatiner

Command to start existing conatiner 
```
docker start <conatiner-id>
```
![start](https://user-images.githubusercontent.com/98541876/194859000-f34f362d-f404-4549-8434-ee7f2dd34c6b.png)


7. Conatiner Stop

Command to stop running conatiner
```
docker stop <conatiner-id>
```
![docker stop](https://user-images.githubusercontent.com/98541876/194859042-db5e7aab-f08b-4ce0-9ec9-fa3e8a648bd5.png)

8. Conatiner force stop

Command to force stop the crunning conatiner

```
docker kill <conatiner-id>
```
![docker kill](https://user-images.githubusercontent.com/98541876/194859070-478c9363-0490-44db-a742-89fb86ccfe81.png)

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
![delete container](https://user-images.githubusercontent.com/98541876/194859108-5c5ce9ee-2e28-46c1-a523-ffb3781b1241.png)

11. List of running conatiners

Command use to list the local running conatiners
```
docker ps
```
![Ps](https://user-images.githubusercontent.com/98541876/194859144-7d8dd120-a2d7-42c9-a27f-e8c7946b3771.png)


12. Entering running conatiner

Command used to enter into running container
```
docker exec -t <container-id> bash
```
![entering container](https://user-images.githubusercontent.com/98541876/194859175-0513d058-c7ba-4e77-b1fb-849f3c38fe4c.png)

13. Logs

Command use to check logs of running conatiner
```
docker logs <container-id> -f
```
![docker logs](https://user-images.githubusercontent.com/98541876/194859246-3a1c87ae-4c1f-4470-8b80-6a1aba9ba000.png)


14. Create volume

Command use to create volume
```
docker volume create <volume_name>
```
![create volume](https://user-images.githubusercontent.com/98541876/194859278-1cfdde6e-0350-49f6-89c5-950fa8bdc703.png)


15. List volumes
Command used to list all volumes
```
docker volume ls
```
![list of volumes](https://user-images.githubusercontent.com/98541876/194859335-9c90b064-a6b3-48f7-8a30-88370c84c266.png)

