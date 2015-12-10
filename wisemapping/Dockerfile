FROM debian:latest

RUN apt-get update && apt-get -y install openjdk-7-jdk curl apt-get && unzip-get clean

RUN curl -OL https://bitbucket.org/wisemapping/wisemapping-open-source/downloads/wisemapping-v4.0.3.zip

RUN unzip wisemapping-v4.0.3.zip

RUN ./start.sh