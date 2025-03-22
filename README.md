# docker-portainer

```
docker swarm init
docker network create --driver overlay --attachable traefik
docker stack deploy -c docker-compose.yml portainer
```
