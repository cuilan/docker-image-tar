# docker-image-tar

github workflow to build docker image tar.

### linux/amd64

```shell
unzip docker-image-tar.zip
tar -zxvf amd64-image.tar.gz
docker load < ${image}.tar 
```

### linux/386

```shell
unzip docker-image-tar.zip
tar -zxvf 386-image.tar.gz
docker load < ${image}.tar 
```

### linux/arm64/v8

```shell
unzip docker-image-tar.zip
tar -zxvf arm64_v8-image.tar.gz
docker load < ${image}.tar 
```
