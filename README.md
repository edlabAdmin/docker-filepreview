# Docker Container for File Preview

[![Build Status](https://travis-ci.org/ryanhanwu/docker-filepreview.svg?branch=master)](https://travis-ci.org/ryanhanwu/docker-filepreview)
[![](https://images.microbadger.com/badges/version/ryanhanwu/docker-filepreview.svg)](https://microbadger.com/images/ryanhanwu/docker-filepreview "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/ryanhanwu/docker-filepreview.svg)](https://microbadger.com/images/ryanhanwu/docker-filepreview "Get your own image badge on microbadger.com")
[![Docker Automated build](https://img.shields.io/docker/automated/ryanhanwu/docker-filepreview.svg)](https://hub.docker.com/r/ryanhanwu/docker-filepreview/ "Get your own image badge on https://shields.io/#/examples/build")

[![Docker Hub](http://dockeri.co/image/ryanhanwu/docker-filepreview "Docker Hub")](https://registry.hub.docker.com/u/ryanhanwu/docker-filepreview/)

A docker image contains everything you need for file previewing, based on [Julien Rottenberg's ffmpeg](https://hub.docker.com/r/jrottenberg/ffmpeg/)

This docker container includes

- [unoconv](https://github.com/dagwieers/unoconv)
- [Ghostscript](https://www.ghostscript.com/)
- [Imagemagick](https://www.imagemagick.org/script/index.php)
- [ffmpeg](https://www.ffmpeg.org/)

## Usage

- TBA

## Test

- TBA

```
docker run -v $PWD/test:/tmp ryanhanwu/docker-filepreview unoconv -f pdf /tmp/file.doc
```

## References

- Use the list of `hyphen-*` and `font-*` packages from [instructure/libreoffice](https://hub.docker.com/r/instructure/libreoffice/)
