## Image build
```
docker build --no-cache -f Dockerfile -t $IMAGE_NAME:$IMAGE_TAG .
```

## Run container
```
docker run --name $CONTAINER_NAME -p $HOST_PORT:80 $IMAGE_NAME:$IMAGE_TAG
```
