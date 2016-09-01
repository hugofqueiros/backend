# Docker

## Commands

### Get Container ID
```sh
docker ps
```

## MacOs
Run this command to configure your shell:
```sh
docker-machine start default

eval "$(docker-machine env default)"
```

docker-machine env default

## Docker machine (same as boot2docker)
docker-machine ls

## Run a webserver [nginx] in a Container with:
```sh
docker run -d -p 8000:80 nginx
```
