# Eureka discovery service [![Build Status](https://travis-ci.com/jaarques-uoc/eureka-ws.svg?branch=master)](https://travis-ci.com/jaarques-uoc/eureka-ws)

Command line tools:
* Spring boot:
    * build: `./gradlew build`
    * run: `./gradlew bootRun`
* Docker:
    * build: `docker build --tag=eureka-ws .`
    * run: `docker run -p 7100:8761 -t eureka-ws`
    * stop: `docker stop $(docker ps -q --filter ancestor=eureka-ws)`
    * stop all containers: `docker stop $(docker ps -a -q)`

* Urls:
    * Travis CI history: https://travis-ci.com/jaarques-uoc/eureka-ws/
    * Docker image: https://cloud.docker.com/repository/docker/jaarquesuoc/eureka-ws
    * Heroku app: https://eureka-ws.herokuapp.com/
