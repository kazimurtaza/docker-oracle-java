## Java Dockerfile


This repository contains **Dockerfile** of [Java](https://www.java.com/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/cogniteev/oracle-java/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Base Docker Image

* [ubuntu](https://registry.hub.docker.com/_/ubuntu/)


### Docker Tags

`cogniteev/oracle-java` provides multiple tagged images:

* `latest` (default): Oracle Java 8 JDK (alias to `java8`)
* `java6`: Oracle Java 6 JDK
* `java7`: Oracle Java 7 JDK
* `java8`: Oracle Java 8 JDK

For example, you can run a `Oracle Java 7` container with the following command:

    docker run -it --rm cogniteev/oracle-java:java8 java -version


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://registry.hub.docker.com/u/cogniteev/oracle-java/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull cogniteev/oracle-java`

### Usage

    docker run -it --rm cogniteev/oracle-java

#### Run `java`

    docker run -it --rm cogniteev/oracle-java java

#### Run `javac`

    docker run -it --rm cogniteev/oracle-java javac
