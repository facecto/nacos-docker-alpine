# nacos-docker-alpine
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

## About facecto
I'm Jon, a developer.