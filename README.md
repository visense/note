# virtual-dsm
/etc/docker/daemon.json
```
{
  "bip": "172.5.0.1/16",
  "default-address-pools": [
    {
      "base": "172.6.0.0/16",
      "size": 24
    }
  ]
}
```
```
systemctl restart docker
docker container restart nas
```
