### Build application
Build the Docker image manually by cloning the Git repo.
```
$ git clone https://github.com/...
$ docker build -t ...
```

### Download precreated image
You can also just download the existing image from [DockerHub]
```
docker pull ...
```

### Run the container
Create a container from the image.
```
$ docker run --name my-container -d -p 8080:8080 ...
```

Now visit http://localhost:8080
```
 The hostname of the container is ...and ...
```

### Verify the running container
Verify by checking the container ip and hostname (ID):
```
