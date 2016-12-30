# dockerized-docs-docker

# What is it?#
Dockerzied docker documentation for offline use.

# Image description #
- Base image: `alpine:3.3`
- The docker.github.io master branch is cloned.
- Jekyll is installed using bundle.

# How to use this image #

```console
$ docker run -d genadipost/dockerized-docs-docker

```
You can test it by visiting http://container-ip:8080
