# whale

## Command

### Image

- List(Need to remove Container first)

```shell
docker images
```

- Remove

```shell
docker rmi [image_name]
```

```shell
# Remove unuse images
docker image prune
```

- Inspect

```shell
docker image inspect [image_id]
```

### Container

- Execute

```shell
docker run []
```

- List

```shell
# a: all(Show not running Container also)
docker ps [-a]
```

- Remove

```
docker rm [container_name]
```
