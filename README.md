# virtual-dsm
```
docker run -itd --name nas -p 80:5000 -p 22:22 -p 445:445 -p 139:139 --cap-add NET_ADMIN -v /mnt/e/Nas:/storage -e DISK_SIZE=60G -e RAM_SIZE=8G -e CPU_CORES=8 vdsm/virtual-dsm
```
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
```
eyJhIjoiM2FlZmFlMDIwZDRmM2YxZWI3ZGNmNGIxZDkzYWFlZjEiLCJ0IjoiMWY1ZmU2OTQtOTU4ZS00NGNlLWFkODMtYTgzODBmOTQ3ZmQzIiwicyI6Ik56STNNekV6Tm1RdE5HUTFOQzAwWTJRNUxUaGxNVEF0Tm1FellXVXdOekl6TlRVeSJ9
```
