# Supported tags and respective `Dockerfile` links

* `java6`, 6u45 JDK [(Dockerfile)](https://github.com/cogniteev/docker-oracle-java/blob/master/oracle-java6/Dockerfile)
* `java7`, 7u80 JDK [(Dockerfile)](https://github.com/cogniteev/docker-oracle-java/blob/master/oracle-java7/Dockerfile)
* `java8`, `latest`, 8u92 [(Dockerfile)](https://github.com/cogniteev/docker-oracle-java/blob/master/oracle-java8/Dockerfile)
* `java9`, 9b116 JDK [(Dockerfile)](https://github.com/cogniteev/docker-oracle-java/blob/master/oracle-java9/Dockerfile)

[![ImageLayers.io](https://badge.imagelayers.io/cogniteev%2Foracle-java:latest.svg)](https://imagelayers.io/?images=cogniteev%2Foracle-java:latest,cogniteev%2Foracle-java:java6,cogniteev%2Foracle-java:java7,cogniteev%2Foracle-java:java8,cogniteev%2Foracle-java:java9)

# Base Docker Image

* [ubuntu:16.04](https://registry.hub.docker.com/_/ubuntu/)

# Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/cogniteev/oracle-java/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull cogniteev/oracle-java`

### Usage

    docker run -it --rm cogniteev/oracle-java

#### Run `java`

    docker run -it --rm cogniteev/oracle-java java

#### Run `javac`

    docker run -it --rm cogniteev/oracle-java javac

# LICENSE

MIT
