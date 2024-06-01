# DockerSubmissions
My Docker Exercises Submission
# Exercise1.1_GettingStarted
## Commands: 
### Container 1:
#### $ docker run nginx
#### $ docker container ls control + c
#### $ docker run -d nginx

### Container 2:
#### $ docker run nginx
#### $ docker container ls control + c
#### $ docker run -d nginx

### Container 3:
#### $ docker run nginx
#### $ docker container ls control + c
#### $ docker run -d nginx

### Stop two of the containers and leave one container running.
#### $ docker container stop 82
#### $ docker container stop 8a
#### $ docker ps -a

# Exercise1.2_CLEAN UP
## Commands:
### Clean the Docker daemon by removing all images and containers:
#### $ docker container prune
#### $ docker image prune
#### $ docker ps -a
#### $ docker image ls

# EXERCISE 1.3: SECRET MESSAGE
## Commands:
### Image devopsdockeruh/simple-web-service:ubuntu will start a container that outputs logs into a file
#### $ docker run -d --rm -it --name secret-message -it devopsdockeruh/simple-web-service:ubuntu
#### $ docker exec -it secret-message bash
### Go inside the running container and use tail -f ./text.log to follow the logs. Every 10 seconds the clock will send you a "secret message"
#### $ tail -f ./text.log
### Secret Message
#### Secret message is: 'You can find the source code here: https://github.com/docker-hy'

