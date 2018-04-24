Docker can use below file system as stroage.
* vfs
* devicemapper
* btrfs
* aufs
* overlay

> example
```shell
echo DOCKER_OPTS=\"-s overlay" >> /etc/default/docker
```
