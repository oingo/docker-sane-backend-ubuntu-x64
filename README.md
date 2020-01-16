## SANE Backend (with libusb1.0) build environment (Ubuntu) Dockerfile


### Base Docker Image

* [ubuntu:18.04](https://registry.hub.docker.com/u/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download : `docker pull oingo/docker-ubuntu-sane-backend-libusb1-build`


### Usage

    docker run -it -v <sane-backend-volume>:/root/project oingo/docker-ubuntu-sane-backend-libusb1-build /bin/bash
