# Ubuntu 16.04 (Xenial) Ansible Test Container

[![Docker Automated Build](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg?maxAge=2592000)](https://hub.docker.com/r/linconf/ubuntu1604/)

Ubuntu 16.04 (Xenial) Docker container for Ansible playbook and role testing.

## How to Use

1. Pull the image from Docker Hub
  - `docker pull linconf/ubuntu1604:latest`
2. Run a container from the image:
  - `docker run --detach --privileged linconf/ubuntu1604:latest`

## How to Build Locally

1. Download the distributions Dockerfile
2. From the download directory, run:
  - `docker build -t <dockerfile-name> .`

[![Analytics](https://cjs-beacon.appspot.com/UA-10006093-3/github/linconf/docker-ubuntu1604-ansible
?pixel)](https://github.com/linconf/docker-test-containers/ubuntu/16.04/)
