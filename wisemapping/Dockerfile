FROM debian:latest

RUN apt-get update && apt-get -y install openjdk-7-jdk curl && apt-get clean

RUN curl -OL https://bitbucket.org/wisemapping/wisemapping-open-source/downloads/wisemapping-v4.0.3.zip

RUN tar -zxvf wisemapping-v4.0.3.zip

RUN ./start.sh