# Ubuntu 14.04 (Trusty) Ansible Test Container

[![Docker Automated Build](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg?maxAge=2592000)](https://hub.docker.com/r/linconf/ubuntu1404/)

Ubuntu 14.04 (Trusty) Docker container for Ansible playbook and role testing.

## How to Use

1. Pull the image from Docker Hub
  - `docker pull linconf/ubuntu1404:latest`
2. Run a container from the image:
  - `docker run --detach --privileged linconf/ubuntu1404:latest`

## How to Build Locally

1. Download the distributions Dockerfile
2. From the download directory, run:
  - `docker build -t <dockerfile-name> .`

[![Analytics](https://cjs-beacon.appspot.com/UA-10006093-3/github/linconf/docker-ubuntu1404-ansible
?pixel)](https://github.com/linconf/docker-test-containers/ubuntu/14.04/)
