# Docker Containers for Ansible Testing

[![Docker Automated Build](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg?maxAge=2592000)](https://hub.docker.com/r/linconf/debian8/)

This repository holds Dockerfiles for building Ansible test containers. The containers
are automatically built on [Docker Hub](https://hub.docker.com/u/linconf/) whenever this
repository is updated or upstream OS distribution containers are rebuilt.

Currently supports the following distributions:

- [CentOS 6.x](https://github.com/linconf/docker-test-containers/tree/master/centos/6)
- [CentOS 7.x](https://github.com/linconf/docker-test-containers/tree/master/centos/7)
- [Debian 7](https://github.com/linconf/docker-test-containers/tree/master/debian/7)
- [Debian 8](https://github.com/linconf/docker-test-containers/tree/master/debian/8)
- [Ubuntu 12.04](https://github.com/linconf/docker-test-containers/tree/master/ubuntu/12.04)
- [Ubuntu 14.04](https://github.com/linconf/docker-test-containers/tree/master/ubuntu/14.04)
- [Ubuntu 16.04](https://github.com/linconf/docker-test-containers/tree/master/ubuntu/16.04)

## How to Use

See the instructions per distribution (same directory as the Dockerfile).

## Author and Attribution

This version is maintained by Chad Sheets - [GitHub](https://github.com/cjsheets) | [Blog](http://chadsheets.com/) | [Email](mailto:chad@linconf.com)

Dockerfile Author: [Jeff Geerling](https://github.com/geerlingguy/docker-debian8-ansible), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).

[![Analytics](https://cjs-beacon.appspot.com/UA-10006093-3/github/linconf/docker-debian8-ansible
?pixel)](https://github.com/linconf/docker-test-containers)
