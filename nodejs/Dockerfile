FROM ubuntu
MAINTAINER Justin Walgran <justin@walgran.com>

RUN echo "deb http://archive.ubuntu.com/ubuntu precise main universe" > /etc/apt/sources.list
RUN apt-get update
RUN apt-get upgrade -y

ADD http://nodejs.org/dist/v0.10.22/node-v0.10.22-linux-x64.tar.gz /node.tar.gz
RUN tar xzf node.tar.gz --strip-components=1 -C /usr/local
RUN rm node.tar.gz
