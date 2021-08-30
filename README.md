# nacos-docker-alpine
[![automated](https://badgen.net/badge/icon/docker?icon=docker&label)](https://hub.docker.com/r/facecto/nacos "Docker hub")
![](https://img.shields.io/badge/alpine-3.9-green?logo=alpine)
![](https://img.shields.io/badge/8-jre-alpine.svg?logo=jre)
![](https://img.shields.io/badge/nacos-1.4.2-green.svg)

Nacos website(https://github.com/alibaba/nacos).
## Step1: build
```
cd ./build
sh build.sh
```
## Step2: start mysql
```
cd ./mysql-docker-compose
docker-compose -f mysql5.7.yaml up -d
```
## Step3: start nacos
```
cd ./nacos-docker-compose
docker-compose -f standalone.yaml up -d
```
## Get docker image from hub.docker.com
```
docker pull facecto/nacos:1.4.2
```

## About facecto
I'm Jon, a developer.
