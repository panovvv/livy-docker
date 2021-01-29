# Big data playground: Livy

[![Docker Build](https://img.shields.io/docker/cloud/build/panovvv/livy.svg)](https://cloud.docker.com/repository/docker/panovvv/livy/builds)
[![Docker Pulls](https://img.shields.io/docker/pulls/panovvv/livy.svg)](https://hub.docker.com/r/panovvv/livy)
[![Docker Stars](https://img.shields.io/docker/stars/panovvv/livy.svg)](https://hub.docker.com/r/panovvv/livy)

Livy Docker image built on top of Hadoop+Hive+Spark

## Software

* [Livy 0.7.0-incubating](https://livy.apache.org/docs/0.7.0-incubating/rest-api.html)

## Usage

Take a look [at this repo](https://github.com/panovvv/bigdata-docker-compose)
to see how I use it as a part of a Docker Compose cluster.

## Maintaining

* Docker file code linting:  `docker run --rm -i hadolint/hadolint < Dockerfile`
* [To trim the fat from Docker image](https://github.com/wagoodman/dive)
