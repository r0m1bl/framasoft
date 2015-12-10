FROM debian:latest

RUN apt-get update && apt-get install openjdk-7-jdk && apt-get clean

RUN wget https://bitbucket.org/wisemapping/wisemapping-open-source/downloads/wisemapping-v4.0.3.zip

RUN tar -zxvf wisemapping-v4.0.3.zip

RUN ./start.sh