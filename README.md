# DockerHelp
(Some Linux require running all the following commands as sudo)

<br>

### Pull/download Container Images from Web:
```docker pull [IMAGE URL WITHOUT PROTOCOL]```

### Run First Time:
```docker run [OPTIONS REQUIRED BY CONTAINER] [IMAGE URL WITHOUT PROTOCOL]```


### List Containers:
```docker ps -a```


### Start Containers:
```docker start [CONTAINER ID]```

### Check Container Logs:
```docker logs -f [CONTAINER ID]```

### Stop Containers:
```docker stop [CONTAINER ID]```


### List Images:
```docker images```


### Remove Containers:
```docker rm [CONTAINER ID]```

### Remove Images:
```docker image rm [IMAGE ID]```