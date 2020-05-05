# Quasar-cli
[![GitHub tag](https://img.shields.io/github/tag/xyeeeChen/quasar-cli.svg)](https://github.com/xyeeeChen/quasar-cli/releases)
[![Docker Pulls](https://img.shields.io/docker/pulls/yeechen/quasar-cli.svg)](https://hub.docker.com/r/yeechen/quasar-cli/)

Docker image for quasar-cli.

* Node: `14.1.0`
* Alpine: `3.10`
* Quasar: `1.0.4`

## Usage

```sh
docker run --rm -it \
  -v $PWD:$PWD
  -w $PWD
  yeechen/quasar-cli /bin/sh
```