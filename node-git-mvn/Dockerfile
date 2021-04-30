FROM ubuntu:20.04

RUN apt-get update && apt-get install -y curl && curl -sL https://deb.nodesource.com/setup_current.x | bash - 

ENV DEBIAN_FRONTEND="noninteractive" TZ="Europe/London"
RUN apt-get update && apt-get install -y git openjdk-11-jdk maven nodejs
