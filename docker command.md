# Docker
## Commands used to create containers on docker:-
### Pull Images:
```
docker pull hello-world
```
```
docker pull nginx
```
```
docker pull httpd
```
### for run contaner:
```
docker run -it {docker name}
```
### See Images:
```
docker images
```
### List of Containers:
```
docker ps
```
### Port Forwarding:
```
docker run -p on which port you like:server port server name
docker run -p 5000:80 nginx
```
### Stop Container:
```
Docker stop nginx
```
```
Docker stop apache
```
### Remove Container:
```
Docker rm nginx
```
```
Docker rm apache
```
### Kill Container:
```
docker kill nginx
```
```
docker kill apache
```
### Microk8s install:
```
sudo snap install microk8s --classic
```
### Install nginx:
```
apt install nginx
```
