# 0verStudentDocker

## Install
```
git clone https://github.com/0verseas/0verStudentDocker.git
cd 0verStudentDocker
git submodule init
git submodule update
cp app/src/env.js.example app/src/env.js
```
edit the config file in ``app/src/env.js``  
add nginx setting file in ``nginx`` folder (ex: ``cp -rp /etc/nginx/* nginx/`` )

## Deploy
### Run
```
docker-compose up -d
```
### Stop
```
docker-compose down
```

## Update submodule
```
git submodule update --recursive --remote
```
