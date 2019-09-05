
# Docker LEMP Stack for Wordpress

This repository is only meant for education purpose and should not be used in production.

The Docker setup is based on following repository: https://github.com/urre/wordpress-nginx-docker-compose

### Useful Docker Commands

Login to the docker container

```shell
docker exec -it myapp-wordpress bash
```

Stop

```shell
docker-compose stop
```

Down (stop and remove)

```shell
docker-compose down
```

Cleanup

```shell
docker-compose rm -v
```

Recreate

```shell
docker-compose up -d --force-recreate
```

Rebuild docker container when Dockerfile has changed

```shell
docker-compose up -d --force-recreate --build
```
