
lang Dockerfile
===============
[![Docker Hub; nimmis/alpine--golang](https://img.shields.io/badge/dockerhub-nimmis%2Falpine--golang-green.svg)](https://registry.hub.docker.com/u/nimmis/alpine-golang)

Docker container with GO programming language build ontop of Alpine to get the size down from over the official 
golang sized [![](https://badge.imagelayers.io/golang:latest.svg)](https://imagelayers.io/?images=golang:latest) to the latest (1.8) of nimmis/alpine-golang [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang.svg)](https://microbadger.com/images/nimmis/alpine-golang "Get your own image badge on microbadger.com")

Based on Alpine [![Docker Hub; nimmis/alpine--glibc](https://img.shields.io/badge/dockerhub-nimmis%2Falpine--glibc-green.svg)](https://registry.hub.docker.com/u/nimmis/alpine-micro) with
glibc,  working init process and syslog. For more information on how to set upp services, please read the dockumentation for [nimmis/alpine-micro](https://registry.hub.docker.com/u/nimmis/alpine-micro)

### Installation

This container should normaly run as a daemon i.e with the -d flag attached

	docker run -d --name go nimmis/alpine-golang

Accessing the container with a shell can be done with

	docker exec -ti go /bin/sh

## Issues

If you have any problems with or questions about this image, please contact us by submitting a ticket through a [GitHub issue](https://github.com/nimmis/docker-alpine-glibc/issues "GitHub issue")

1. Look to see if someone already filled the bug, if not add a new one.
2. Add a good title and description with the following information.
 - if possible an copy of the output from **cat /etc/BUILDS/*** from inside the container
 - any logs relevant for the problem
 - how the container was started (flags, environment variables, mounted volumes etc)
 - any other information that can be helpful

## Contributing

You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.



This image contains version 1.2.2 to the latest version (atm 1.9.1), the versions are nimmis/alpine-golang:<tag> where tag is

| Tag    | Go Version | Container size |
| ------ | ---------- | -------------- |
| latest | latest (atm 1.9.1) | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang.svg)](https://microbadger.com/images/nimmis/alpine-golang "Get your own image badge on microbadger.com") |
| 1.9.1 | 1.9.1 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.9.1.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.9.1 "Get your own image badge on microbadger.com") |
| 1.9 | 1.9 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.9.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.9 "Get your own image badge on microbadger.com") |
| 1.8.4 | 1.8.4 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.8.4.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.8.4 "Get your own image badge on microbadger.com") |
| 1.8.3 | 1.8.3 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.8.3.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.8.3 "Get your own image badge on microbadger.com") |
| 1.8.1 | 1.8.1 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.8.1.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.8.1 "Get your own image badge on microbadger.com") |
| 1.8 | 1.8 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.8.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.8 "Get your own image badge on microbadger.com") |
| 1.7.5 | 1.7.5 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.7.5.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.7.5 "Get your own image badge on microbadger.com") |
| 1.7.4 | 1.7.4 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.7.4.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.7.4 "Get your own image badge on microbadger.com") |
| 1.7.3 | 1.7.3 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.7.3.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.7.3 "Get your own image badge on microbadger.com") |
| 1.7  | 1.7 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.7.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.7 "Get your own image badge on microbadger.com") |
| 1.6.3  | 1.6.3 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.6.3.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.6.3 "Get your own image badge on microbadger.com") |
| 1.6.2  | 1.6.2 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.6.2.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.6.2 "Get your own image badge on microbadger.com") |
| 1.6    | 1.6 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.6.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.6 "Get your own image badge on microbadger.com") |
| 1.5.3  | 1.5.3 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.5.3.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.5.3 "Get your own image badge on microbadger.com") |
| 1.5    | 1.5 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.5.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.5 "Get your own image badge on microbadger.com") |
| 1.4.2  | 1.4.2 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.4.2.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.4.2 "Get your own image badge on microbadger.com") |
| 1.4.1  | 1.4.1 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.4.1.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.4.1 "Get your own image badge on microbadger.com") |
| 1.4    | 1.4 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.4.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.4 "Get your own image badge on microbadger.com") |
| 1.3.3  | 1.3.3 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.3.3.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.3.3 "Get your own image badge on microbadger.com") |
| 1.3    | 1.3 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.3.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.3 "Get your own image badge on microbadger.com") |
| 1.2.2  | 1.2.2 | [![](https://images.microbadger.com/badges/image/nimmis/alpine-golang:1.2.2.svg)](https://microbadger.com/images/nimmis/alpine-golang:1.2.2 "Get your own image badge on microbadger.com") |

