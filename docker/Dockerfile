FROM ubuntu:18.04

RUN apt update
RUN apt-get install -y software-properties-common build-essential
RUN add-apt-repository ppa:team-gcc-arm-embedded/ppa
RUN apt update
RUN apt install -y gcc-arm-embedded

WORKDIR /vesc
