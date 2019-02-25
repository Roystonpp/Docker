# Docker
Deploying with docker

Install Docker

Once installed clone this repository

https://github.com/Roystonpp/Docker.git

Go inside the folder where the docker file is located and run:

```
docker build -t <name>:<tag> .
```
Alternativley you can just run this command to pull the nginx image from the docker directly
```
docker pull nginx
```
After the nginx image has been pulled type:
```
docker images
```
You will see the nginx image in your repository
