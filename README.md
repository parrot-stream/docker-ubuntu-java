# **centos-java**
___

### Description
___

This image adds Oracle Java Developmt Kit to a base [**Ubuntu**](https://hub.docker.com/r/_/ubuntu/) Linux distribution.


The *latest* tag of this image is build using the last available Ubuntu Docker image and the last available Oracle JDK.
You can pull it with:

    docker pull mcapitanio/ubuntu-java


You can also find other images based on different Ubuntu / JDK releases, using different tags in the following form:

    docker pull mcapitanio/ubuntu-java:[ubuntu-release]-[jdk-release]


For example, if you want a Ubuntu Trusty (14.04) release with Oracle JDK release 8u20 you can pull the image with:

    docker pull mcapitanio/ubuntu-java:trusty-8u20


Run with Docker Compose:

    docker-compose run ubuntu-java java -version


Run with Docker run:

    docker run mcapitanio/ubuntu-java java -version


Available tags:

- Ubuntu Xenial (16.04), Java 8u102 (xenial-8u102, [latest](https://github.com/mcapitanio/docker-ubuntu-java/blob/latest/Dockerfile))
- Ubuntu Xenial (16.04), Java 7u80 ([xenial-7u80](https://github.com/mcapitanio/docker-ubuntu-java/blob/xenial-7u80/Dockerfile))