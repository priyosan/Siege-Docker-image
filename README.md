# Siege-Docker-image

# Docker Image for Siege

How to use.

#setup

$ git clone https://github.com/yokogawa-k/docker-siege.git
$ cd docker-siege
$ docker build -t yokogawa/siege .
help

$ docker run --rm -t yokogawa/siege
If you use ./run script.

$ ./run
Performance test

$ docker run --rm -t yokogawa/siege -d1 -r10 -c25 example.com
If you use ./run script.

$ ./run -d1 -r10 -c25 example.com
use bash

$ ./run bash
fig

$ fig up -d
$ fig logs
