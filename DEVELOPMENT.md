1. compare changes in /gwy and /gwy-v2 folders, and migrate changrs necesssary
2. run `make build` to build namely docker images
3. run `docker build -t castlery/gen-grpc-gateway:1.28_2 -f Dockerfile-gw .` to generate new image for grpc gate generation
4. push image to dockerhub
```
docker push castlery/gen-grpc-gateway:1.28_2
```