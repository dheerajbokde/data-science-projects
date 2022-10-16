# Docker Commands

### 1. version 
- to check docker version
```git
Example: docker --version
                or
         docker -v
```
![image](https://user-images.githubusercontent.com/5664029/195972046-9826c959-c69f-4912-8bed-306475c63fe0.JPG)


### 2. pull 
- to download an image form docker hub
```git
Example: docker pull hello-world
```
![image](https://user-images.githubusercontent.com/5664029/195972101-a28c442f-acdc-4516-8f7f-caf9f167fabe.JPG)

### 3. images
- to show the list of one/all available images
```git
Example: docker images
```
![image](https://user-images.githubusercontent.com/5664029/195972421-4361a815-27a0-4747-9f7e-6ba755b7aa61.JPG)
```git
Example: docker images hello-world 
```
![image](https://user-images.githubusercontent.com/5664029/195972507-30244c9e-f65d-4376-8101-ce9a0605c6f4.JPG)

### 4. run
- to start new container from an image
```git 
Example: docker run hello-world 
```
![image](https://user-images.githubusercontent.com/5664029/195972743-89fbbcda-0eba-4a1f-9a9b-fe7674cfb9ca.JPG)

### 5. run 
- to start new container in background from an image and map it to a port
```git 
Example: docker run -d -p 80:80 docker/getting-started 
```
![image](https://user-images.githubusercontent.com/5664029/195972886-569e6c70-7498-41e1-9199-cd52127b1285.JPG)

### 6. ps
- to show a list of running containers
```git
Example: docker ps
```
![image](https://user-images.githubusercontent.com/5664029/195972941-904d14c8-3ee8-4cb0-a1e0-c591f8ae27a4.JPG)

### 7. stop <container_id>
- to stop a running container
```git
Example: docker stop 34765829d759
```
![image](https://user-images.githubusercontent.com/5664029/195973043-18fbf231-3bb5-42cf-91a3-4abe2b977b6e.JPG)

### 8. rm <container_id>
- to delete a running container
```git
Example: docker rm -f ff7c5420d1db0
```
![image](https://user-images.githubusercontent.com/5664029/195973044-71b6ba7e-2950-4195-8d4f-0d68d4218cea.JPG)

### 9. rmi <image>
- to delete an image
```git 
Example: docker rmi -f hello-world
```
![image](https://user-images.githubusercontent.com/5664029/195973045-8c0ba680-09d0-4ae1-a895-dbff1d4807f6.JPG)

### 10. rename
- to rename a container
```git
Example: docker rename ccba6a1e6d62 getting-started-new
```
![image](https://user-images.githubusercontent.com/5664029/195973046-59802368-8703-4869-b79d-7a00eff92724.JPG)

### 11. logs <container_id>
- to show the logs of a container
```git
Example: docker logs ccba6a1e6d62
```
![image](https://user-images.githubusercontent.com/5664029/195973047-90577990-4865-4795-aac0-cebb366aceab.JPG)

### 12. stats
- to show stats of running container
```git
Example: docker stats
```
![image](https://user-images.githubusercontent.com/5664029/195973048-8c619429-ee71-47cf-beca-b7122f1802a7.JPG)

### 13. stop
- to stop a running container
```git
Example: docker stop ccba6a1e6d62
```
![image](https://user-images.githubusercontent.com/5664029/195973049-c4cf3ce5-30a6-4d18-81ac-c7c274540a2a.JPG)

### 14. prune
- to delete all stopped container
```git
Example: docker container prune
```
![image](https://user-images.githubusercontent.com/5664029/195973050-d3f40061-10da-4f3c-979c-acf3503d3c8a.JPG)

### 15. commit <container_id>
- to create an image out of a container
```git
Example: docker commit 67831ba6f277
```
![image](https://user-images.githubusercontent.com/5664029/195973051-26e05b12-2958-4af6-a43f-f608cf21e959.JPG)

### 16. tag <image> <new_image>
- to tag an image
```git
Example: docker tag 64c6baaa3a4e getting-started-local
```
![image](https://user-images.githubusercontent.com/5664029/195973052-5b1a8b3f-e591-438f-8ca2-c84977e350ad.JPG)
