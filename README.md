# Delete-docker-image-with-all-tags

```
docker images | grep busybox | tr -s ' ' | cut -d ' ' -f 2 | xargs -I {} docker rmi busybox:{}
```
