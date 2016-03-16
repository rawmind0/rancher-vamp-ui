rancher-vamp-ui
==============

alpine-vamp-ui image based in alpine-nginx

To build

```
docker build -t <repo>/rancher-vamp-ui:<version> .
```

To run:

```
docker run -it <repo>/rancher-vamp-ui:<version> 
```

## Versions

- `0.8.4` [(Dockerfile)](https://github.com/rawmind0/rancher-vamp-ui/blob/master/Dockerfile)

## Usage

This image compile and deploy to access vamp-ui service. 

The nginx service is started with monit and check for the 80 port is listening.
