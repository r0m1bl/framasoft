FROM debian:latest

MAINTAINER Romain Bouchaud


RUN echo "deb http://http.debian.net/debian jessie-backports main" >> /etc/apt/sources.list

RUN apt-get update && apt-get -y upgrade && apt-get -y install openjdk-8-jdk curl unzip && apt-get clean

RUN curl -OL https://bitbucket.org/wisemapping/wisemapping-open-source/downloads/wisemapping-v4.0.3.zip

RUN unzip wisemapping-v4.0.3.zip

EXPOSE 8080

WORKDIR ./wisemapping-v4.0.3

CMD ["bash", "./start.sh"]