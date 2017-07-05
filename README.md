## MongoDB Dockerfile build on the top of alpine linux

This repository contains **Dockerfile** of [MongoDB](http://www.mongodb.org/) for [Docker](https://www.docker.com/). It is build on the top of lightweight docker image [alpine](https://hub.docker.com/_/alpine/)

### Installation

1. Install [Docker](https://www.docker.com/).

2. Pull from [Docker Hub](https://hub.docker.com/r/yipl/mongo/): `docker pull yipl/mongo`

   (alternatively, you can build an image from this Dockerfile: )
   `docker build -t="yipl/mongo" github.com/xaurav91/docker_mongo_alpine`