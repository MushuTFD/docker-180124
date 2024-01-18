docker run -dp 8080:80 httpd

docker exec -it <containder_id> sh
docker image pull <image_name>:<image_tag>
docker run -dp 9090:80 httpd:2.4-alpine

docker stop <container_id>
docker rm <container_id>

docker rm -f $(docker ps -aq)