# Docker

https://docs.docker.com/samples/library/nginx/

- Create a Docker file 

- Build and run

docker build -t nginx-image .
docker run --name nginx-image -d image
docker run --name nginx-image -d -p 8080:80 nginx-image
docker run --name nginx-image -v /host/path/nginx.conf:/etc/nginx/nginx.conf:ro -d nginx
