# alpine-bash-openssl-keytool

_Bash Shell + curl with SSL support based on Alpine Linux_

[![Docker Automated Build](https://img.shields.io/docker/automated/olopopo/alpine-bash-openssl-keytool.svg)](https://hub.docker.com/r/olopopo/alpine-bash-openssl-keytool/)
[![Docker Pulls](https://img.shields.io/docker/pulls/olopopo/alpine-bash-openssl-keytool.svg)](https://hub.docker.com/r/olopopo/alpine-bash-openssl-keytool/)

- Docker: [olopopo/alpine-bash-openssl-keytool](https://hub.docker.com/r/olopopo/alpine-bash-openssl-keytool/)

## Installation

`docker pull olopopo/alpine-bash-openssl-keytool`

## About the Container

As Base Image i use [Alpine Linux](https://alpinelinux.org/) which is lightweight Distribution with a small surface area for security concerns, but with enough functionality for development and interactive debugging.

To prevent zombie reaping processes i run [dumb-init](https://github.com/Yelp/dumb-init) as PID 1 which forwards signals to all processes running in the container.
