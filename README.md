## Create network docker
```
docker network create --attachable --driver bridge --ipam-driver default --subnet 192.168.255.0/29 mw2
```

## Build image
```
docker build -t iw4x_rcon:1.0 -f Dockerfile_admin .
```





