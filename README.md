# OpenDKIM for docker

This is an image for running [OpenDKIM](http://www.opendkim.org/). This image is based on the lightweight [Alpine Linux](https://alpinelinux.org/).

## Usage

```
docker run -v /etc/my-opendkim.conf:/etc/opendkim/opendkim.conf -p inet:12301
```
