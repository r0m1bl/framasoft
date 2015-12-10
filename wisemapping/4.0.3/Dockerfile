FROM debian:latest

RUN apt-get update && apt-get -y install openjdk-7-jdk curl unzip && apt-get clean

RUN curl -OL https://bitbucket.org/wisemapping/wisemapping-open-source/downloads/wisemapping-v4.0.3.zip

RUN unzip wisemapping-v4.0.3.zip

EXPOSE 8080

CMD ["bash", "./wisemapping-v4.0.3/start.sh"]