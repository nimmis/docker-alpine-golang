
lang Dockerfile
===============
[![Docker Hub; nimmis/golang](https://img.shields.io/badge/dockerhub-nimmis%2Falpine-golang-green.svg)](https://registry.hub.docker.com/u/nimmis/alpine-golang)

Docker container with GO programming language build ontop of Alpine to get the size down from over 800 Mb to 314 Mb

Based on [![Docker Hub; nimmis/alpine-micro](https://img.shields.io/badge/dockerhub-nimmis%2Falpine-micro-green.svg)](https://registry.hub.docker.com/u/nimmis/alpine-micro) with working init process and syslog. For more information on how to set upp services, please read the dockumentation for [nimmis/alpine-micro](https://registry.hub.docker.com/u/nimmis/alpine-micro)

### Installation

This continer should normaly run as a daemon i.e with the -d flag attached

    docker run -d nimmis/alpine-golang

Accessing the container with a bash shell can be done with

	docker exec -ti <container ID> /bin/bash

### TAGs

This image contains version 1.2.2 to the latest version (atm 1.6), the versions are nimmis/alpine-golang:<tag> where tag is

- latest -  this gives the latest version (atm 1.6)
- 1,5,3  -  this is the 1.5.3 version
- 1.5    -  this is the 1.5 version
- 1.4.1  -  this is the the 1.4.1 version
- 1.4.2  -  this is the the 1.4.2 version
- 1.4    -  this is the the 1.4 version
- 1.3.3  -  this is the the 1.3.3 version
- 1.3    -  this is the the 1.3 version
- 1.2.2  -  this is the the 1.2.2 version

