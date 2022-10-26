# litecoin
## Image Creation
### change directory into `docker` directory
```
cd docker
```
### build the image using below command
```
docker build -t litecoin:0.18.1 .
```
### run the container using below command
```
docker run -itd litecoin:0.18.1
```

## running litecoin as k8s container

### change into directory `k8s` and run the below commands
```
kubectl apply -f .
```