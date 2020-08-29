FROM golang:1.16.3-buster

RUN apt update

#pkg-config
RUN apt install -y pkg-config

#Seabolt
RUN wget https://github.com/neo4j-drivers/seabolt/releases/download/v1.7.4/seabolt-1.7.4-Linux-ubuntu-18.04.deb \
    && dpkg -i seabolt-1.7.4-Linux-ubuntu-18.04.deb \
    && rm seabolt-1.7.4-Linux-ubuntu-18.04.deb
