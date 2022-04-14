Docker

containers:
    insolation  
    same os
    containers are actual process
    
Dockerfile for the most part 4 segment
- FROM <IMAGE>
- COPY
- RUN
- CMD


COMMANDS
1  -> docker run <image> (-it will run it in interactive mode)
if this image is there locally then docker will run it
else it will search for it on the docker hub and get best matching result and pull

2  - > docker ps -a
gives all running process or containers

3  -> Build command  sudo docker build -t name_of_imege<directory which contains the dockerfile

4 -> docker run -d --network=host my-container:latest :  run the container with localhost accessible via the host system.

5 ->  docker stop container_id
