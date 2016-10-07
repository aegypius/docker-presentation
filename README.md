Présentation Docker
===================

Pré-requis
----------

1. Installation de Virtualbox
2. [Installation de docker-engine](https://docs.docker.com/engine/installation/linux/debian/)
2. [Installation de docker-machine](https://docs.docker.com/machine/install-machine/)


```shell
docker-machine create --driver virtualbox tests
eval $(docker-machine env tests)
docker info
docker run alpine /bin/echo "Hello World"
```
