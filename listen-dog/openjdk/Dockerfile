ARG JDK_VERSION
FROM openjdk:$JDK_VERSION

MAINTAINER Jover Zhang <joverzh@gmail.com>

RUN yum install -y procps wget &&
    wget -P /bin https://raw.githubusercontent.com/JoverZhang/bash-toolkit/master/docker/listenDog.sh
