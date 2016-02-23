
lang Dockerfile
===============
[![Docker Hub; nimmis/alpine--golang](https://img.shields.io/badge/dockerhub-nimmis%2Falpine--golang-green.svg)](https://registry.hub.docker.com/u/nimmis/alpine-golang)

Docker container with GO programming language build ontop of Alpine to get the size down from over the official 
golang sized (https://badge.imagelayers.io/golang:latest.svg) to the latest (1.6) of nimmis/alpine-golang (https://badge.imagelayers.io/nimmis/alpine-golang:latest.svg)

Based on Alpine [![Docker Hub; nimmis/alpine--micro](https://img.shields.io/badge/dockerhub-nimmis%2Falpine--micro-green.svg)](https://registry.hub.docker.com/u/nimmis/alpine-micro) with working init process and syslog. For more information on how to set upp services, please read the dockumentation for [nimmis/alpine-micro](https://registry.hub.docker.com/u/nimmis/alpine-micro)

### Installation

This container should normaly run as a daemon i.e with the -d flag attached

	docker run -d --name go nimmis/alpine-golang

Accessing the container with a shell can be done with

	docker exec -ti go /bin/sh

### TAGs

This image contains version 1.2.2 to the latest version (atm 1.6), the versions are nimmis/alpine-golang:<tag> where tag is

| Tag    | Go Version | Container size |
| ------ | ---------- | -------------- |
| latest | latest (atm 1.6) | [![](https://badge.imagelayers.io/nimmis/alpine-golang:latest.svg)](https://imagelayers.io/?images=nimmis/alpine-golang:latest) |
| 1.6    | 1.6 | [![](https://badge.imagelayers.io/nimmis/alpine-golang:1.6.svg)](https://imagelayers.io/?images=nimmis/alpine-golang:1.6) |
| 1.5.3  | 1.5.3 | [![](https://badge.imagelayers.io/nimmis/alpine-golang:1.5.3.svg)](https://imagelayers.io/?images=nimmis/alpine-golang:1.5.3) |
| 1.5    | 1.5 | [![](https://badge.imagelayers.io/nimmis/alpine-golang:1.5.svg)](https://imagelayers.io/?images=nimmis/alpine-golang:1.5) |
| 1.4.2  | 1.4.2 | [![](https://badge.imagelayers.io/nimmis/alpine-golang:1.4.2.svg)](https://imagelayers.io/?images=nimmis/alpine-golang:1.4.2) |
| 1.4.1  | 1.4.1 | [![](https://badge.imagelayers.io/nimmis/alpine-golang:1.4.1.svg)](https://imagelayers.io/?images=nimmis/alpine-golang:1.4.1) |
| 1.4    | 1.4 | [![](https://badge.imagelayers.io/nimmis/alpine-golang:1.4.svg)](https://imagelayers.io/?images=nimmis/alpine-golang:1.4) |
| 1.3.3  | 1.3.3 | [![](https://badge.imagelayers.io/nimmis/alpine-golang:1.3.3.svg)](https://imagelayers.io/?images=nimmis/alpine-golang:1.3.3) |
| 1.3    | 1.3 | [![](https://badge.imagelayers.io/nimmis/alpine-golang:1.3.svg)](https://imagelayers.io/?images=nimmis/alpine-golang:1.3) |
| 1.2.2  | 1.2.2 | [![](https://badge.imagelayers.io/nimmis/alpine-golang:1.2.2.svg)](https://imagelayers.io/?images=nimmis/alpine-golang:1.2.2) |

