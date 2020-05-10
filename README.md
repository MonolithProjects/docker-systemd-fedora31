# Fedora31 Ansible Test Image

[![GitHub Actions](https://github.com/MonolithProjects/docker-systemd-fedora31/workflows/Dockerfile%20test/badge.svg?branch=master)](https://github.com/MonolithProjects/docker-systemd-fedora31/actions)
[![DockerHub-layers](https://img.shields.io/microbadger/layers/monolithprojects/systemd-fedora31)](https://hub.docker.com/repository/docker/monolithprojects/systemd-fedora31)
[![DockerHub-pulls](https://img.shields.io/docker/pulls/monolithprojects/systemd-fedora31)](https://hub.docker.com/repository/docker/monolithprojects/systemd-fedora31)
[![DockerHub](https://img.shields.io/docker/cloud/automated/monolithprojects/systemd-fedora31?maxAge=2592000)](https://hub.docker.com/repository/docker/monolithprojects/systemd-fedora31)

Fedora31 docker image with enabled systemd. I am using it with Molecule for Ansible role testing.

## Tags

- `latest`: Latest version of the image

## How-to

  1. Pull image with command `docker pull monolithprojects/systemd-fedora31:latest`  
  2. Run the container from the image: `docker run --detach --privileged --volume=/sys/fs/cgroup:/sys/fs/cgroup:ro monolithprojects/systemd-fedora31:latest`  

## License

MIT
