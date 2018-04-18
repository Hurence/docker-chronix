# docker-chronix
solr chronix docker container


to build

    docker build -t hurence/docker-chronix .


to run

   docker run -p 8983:8983 --name chronix -it hurence/docker-chronix:latest
