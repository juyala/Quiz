# Quiz

1) make a docker image.
docker build -t quiz .

2) check generated images in docker 
docker images 

3) run the image in docker
  docker run --name Quiz -d -p 8888:80 quiz
  
4) check running containers
  docker ps - a

5) docker stop running container

docker stop <container_id>

6) remove containers

docker rm <container_id>
7) remove imgage
docker rmi <image>
  

