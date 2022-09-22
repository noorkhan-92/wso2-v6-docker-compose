# Dockerfile for WSO2 Identity Server v6.0.0 #

This section defines the step-by-step instructions to build an [Alpine](https://hub.docker.com/_/alpine/) Linux based Docker image for WSO2 Identity Server `v6.0.0`.

- download the wso2 zip file for version 6.0.0 `wso2is-6.0.0.zip` and place it in this folder.
- build docker image in dockerfiles/alpine: `docker build -t wso2is:6.0.0-alpine .`
- on Mac M1 it will give aarch64 error. So add --platform linux/amd64 to compile as amd64 and it will use emulation when running. `docker build --platform linux/amd64 -t wso2is:6.0.0-alpine .`


This folder is designed to be used in combination with docker-compose that's defined in the parent folder.
