# Kali

Kali Linux as a docker container.

[![Docker Build](https://github.com/thomasleplus/docker-kali/workflows/Docker/badge.svg)](https://github.com/thomasleplus/docker-kali/actions?query=workflow:"Docker")
[![Docker Stars](https://img.shields.io/docker/stars/thomasleplus/kali)](https://hub.docker.com/r/thomasleplus/kali)
[![Docker Pulls](https://img.shields.io/docker/pulls/thomasleplus/kali)](https://hub.docker.com/r/thomasleplus/kali)
[![Docker Automated](https://img.shields.io/docker/cloud/automated/thomasleplus/kali)](https://hub.docker.com/r/thomasleplus/kali)
[![Docker Build](https://img.shields.io/docker/cloud/build/thomasleplus/kali)](https://hub.docker.com/r/thomasleplus/kali)
[![Docker Version](https://img.shields.io/docker/v/thomasleplus/kali?sort=semver)](https://hub.docker.com/r/thomasleplus/kali)

### Mac/Linux

```
docker run -t --user="$(id -u):$(id -g)" -v "$(pwd):/tmp" thomasleplus/kali
```

Add the `--rm` option if you want to discard the container when you exit it.

### Windows

In `cmd`:

```
docker run -t -v "%cd%:/tmp" thomasleplus/kali
```

In PowerShell:

```
docker run --rm -t -v "${PWD}:/tmp" thomasleplus/kali
```

Add the `--rm` option if you want to discard the container when you exit it.

## Request new tool

Please use [this link](https://github.com/thomasleplus/docker-kali/issues/new?assignees=thomasleplus&labels=enhancement&template=feature_request.md&title=%5BFEAT%5D) (GitHub account required) to request that a new tool be added to the image. I am always interested in adding new capabilities to these images.
