# joyce-boot-docker

build a docker image command:
docker build -t joyce-boot-docker .

run a container with image name, container port = 8030, host machine port = 8031 :
docker run -p 8031:8030 joyce-boot-docker
