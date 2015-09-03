# Debian Jessie base Dockerfile

This repository contains **Dockerfile** of [Debian](http://debian.org/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/puckel/docker-base/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).

## Informations

* Based on Debian Latest (jessie) official Image [debian:latest](https://registry.hub.docker.com/_/debian/)
* Install [Docker](https://www.docker.com/)
* Install [Docker-compose](https://docs.docker.com/compose/install/)
* Added those elements: Define LANG to en_US.UTF-8, Packages (procps, psmisc, net-tools, curl, locales, cron, ca-certificates, vim) and clean up image (man, doc)

## Installation

        docker pull puckel/docker-base

## Build

You can build an image from Github [Dockerfile](https://github.com/puckel/docker-base)

        docker build --rm -t puckel/docker-base .

# Wanna help?

Fork, improve and PR. ;-)
