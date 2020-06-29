# Brothers in ARMs' bind dns server

![GitHub release (latest by date)](https://img.shields.io/github/v/release/biarms/bind?label=Latest%20Github%20release&logo=Github)
![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/biarms/bind?include_prereleases&label=Highest%20GitHub%20release&logo=Github&sort=semver)

[![TravisCI build status image](https://img.shields.io/travis/biarms/bind/master?label=Travis%20build&logo=Travis)](https://travis-ci.org/biarms/bind)
[![CircleCI build status image](https://img.shields.io/circleci/build/gh/biarms/bind/master?label=CircleCI%20build&logo=CircleCI)](https://circleci.com/gh/biarms/bind)

[![Docker Pulls image](https://img.shields.io/docker/pulls/biarms/bind?logo=Docker)](https://hub.docker.com/r/biarms/bind)
[![Docker Stars image](https://img.shields.io/docker/stars/biarms/bind?logo=Docker)](https://hub.docker.com/r/biarms/bind)
[![Highest Docker release](https://img.shields.io/docker/v/biarms/bind?label=docker%20release&logo=Docker&sort=semver)](https://hub.docker.com/r/biarms/bind)

## Overview
This project, inspired from sameersbn/docker-bind, build a [bind](http://www.bind.org/) container.

Resulting docker images are pushed on [docker hub](https://hub.docker.com/r/biarms/bind/).

*Caution*: only arm32v7, arm64v8 and amd64 images are produced (no arm32v6), so this image won't be supported on Raspberry Zero or one.

## References
 - https://github.com/sameersbn/docker-bind

## How to build locally
1. Option 1: with CircleCI Local CLI:
   - Install [CircleCI Local CLI](https://circleci.com/docs/2.0/local-cli/)
   - Call `circleci local execute`
2. Option 2: with make:
   - Install [GNU make](https://www.gnu.org/software/make/manual/make.html). Version 3.81 (which came out-of-the-box on MacOS) should be OK.
   - Call `make build`
