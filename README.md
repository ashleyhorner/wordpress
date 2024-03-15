## WordPress Docker

```
docker compose up -d
```

### Shutdown and cleanup

The command [`docker compose down`](https://docs.docker.com/engine/reference/commandline/compose_down/) removes the
containers and default network, but preserves your WordPress database.

The command 
```
docker compose down --volumes
```
removes the containers, default
network, and the WordPress database.

Adapted from: https://github.com/docker/awesome-compose/tree/master/official-documentation-samples/wordpress/
