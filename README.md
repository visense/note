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
```
eyJhIjoiM2FlZmFlMDIwZDRmM2YxZWI3ZGNmNGIxZDkzYWFlZjEiLCJ0IjoiMWY1ZmU2OTQtOTU4ZS00NGNlLWFkODMtYTgzODBmOTQ3ZmQzIiwicyI6Ik56STNNekV6Tm1RdE5HUTFOQzAwWTJRNUxUaGxNVEF0Tm1FellXVXdOekl6TlRVeSJ9
```
