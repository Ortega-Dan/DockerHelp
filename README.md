# DockerHelp
(Some Linux require running all the following commands as sudo)

<br>

### Pull/download Container Images from Web:
```docker pull [IMAGE URL WITHOUT PROTOCOL]```

### Run First Time:
```docker run [OPTIONS REQUIRED BY CONTAINER] [IMAGE URL WITHOUT PROTOCOL]```
___
## Containers
### List Containers:
```docker ps -a```

### Start Containers:
```docker start [CONTAINER ID]```

### Check Container Logs:
```docker logs -f [CONTAINER ID]```

### Stop Containers:
```docker stop [CONTAINER ID]```

### Remove Containers:
```docker rm [CONTAINER ID]```
___
## Images
### List Images:
```docker images```

### Remove Images:
```docker image rm [IMAGE ID]```