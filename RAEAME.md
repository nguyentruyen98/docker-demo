1.  Run docker image

```
docker run <image name>
docker run docker/whalesay cowsay boo
```

```
-d : Run container in the background
```

2. List all the running container

```
docker ps
```
```
-a : List all container
```

3. Stop docker container

```
docker stop <container name or container id>
```

4. Remove docker container

```
docker rm <container name or container id>
```

5. Remove docker image 

```
docker rmi <docker image name or image id>
```

6. Pull remove image

```
docker pull <image name>
```

7. Exec docker container
   

```
docker exec <container id> <command>
```

8. List docker image

```
docker image
```