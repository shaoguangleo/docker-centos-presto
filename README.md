# About

Dockerfile to build a presto image based on CentOS.

# How to run

Just type the following commands

```
$ docker run -it -e DISPLAY=unix$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix shaoguangleo/centos-presto
```

As we all know, the version can be `latest` or `$ cat VERSION`

# travis

[![Build Status](https://www.travis-ci.org/shaoguangleo/docker-centos-presto.svg?branch=master)](https://www.travis-ci.org/shaoguangleo/docker-centos-presto)
