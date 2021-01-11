# python-ubuntu-image


#### build
```
docker build --build-arg=UBUNTU_VERSION=18.04 \
             -t python:3.6-ubuntu18.04 -f Dockerfile .
```

#### image
```
docker pull docker.io/chongchuanbing/python:3.6-ubuntu18.04
```