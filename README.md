# **ubuntu-java**
___

### Description
___

This image adds Oracle Java Development Kit to a base [**Ubuntu**](https://hub.docker.com/r/_/ubuntu/) Linux distribution.

The *latest* tag of this image is build using the latest available Ubuntu Docker image and the latest available Oracle JDK.
You can pull it with:

    docker pull parrotstream/ubuntu-java


You can also find other images based on different Ubuntu / JDK releases, using different tags in the following form:

    docker pull parrotstream/ubuntu-java:[ubuntu-release]-[jdk-release]


For example, if you want a Ubuntu Trusty (14.04) release with Oracle JDK release 8 you can pull the image with:

    docker pull parrotstream/ubuntu-java:trusty-8


Run with Docker Compose:

    docker-compose run ubuntu-java java -version


Run with Docker run:

    docker run parrotstream/ubuntu-java java -version


Available tags:

- Ubuntu Zesty (17.04), Java 8 ([zesty-8](https://github.com/parrot-stream/docker-ubuntu-java/blob/zesty-8/Dockerfile), [latest](https://github.com/parrot-stream/docker-ubuntu-java/blob/latest/Dockerfile))
- Ubuntu Xenial (16.04), Java 8 ([xenial-8](https://github.com/parrot-stream/docker-ubuntu-java/blob/xenial-8/Dockerfile))
- Ubuntu Xenial (16.04), Java 7 ([xenial-7](https://github.com/parrot-stream/docker-ubuntu-java/blob/xenial-7/Dockerfile))
