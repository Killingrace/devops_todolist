# Instruction to Docker Image

This is a short instruction for Docker Image of this project

## DockerHub

Easy access to Dockerfile from [DockerHub](https://hub.docker.com/repository/docker/killingrace/todoapp/general)

## How to run

You can easily create container from this link following this command:

```bash
docker run -p 8080:8080 killingrace/todoapp
```

- To bind container port on another by changing ```-p [your port]:8080```
- Optionally you can add your own container name just adding ```--name [your container name]``` parameter.

## Accessing to container app

To access application just follow the links:

1. [API](http://localhost:8000/api/)
2. [Landing Page](http://localhost:8000)
