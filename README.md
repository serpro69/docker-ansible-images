[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://stand-with-ukraine.pp.ua)

# Docker Ansible Images 

Docker images of various Linux distributions that I use for testing Ansible playbooks, roles and collections.

These images provide minimal set of dependencies to be able to run [Ansible](https://docs.ansible.com/ansible/latest/index.html).

The images are built on top of official docker images for a given Linux distribution, unless otherwise specified.

## Contents

| Docker Image                                                                                                                  | App Ver                      | Dockerhub Path                                                         |
|-------------------------------------------------------------------------------------------------------------------------------|------------------------------|------------------------------------------------------------------------|
| <img src="docs/assets/images/thumbnails/debian.svg" height=36/> `serpro69/ansible-debian`                                     |                              | https://hub.docker.com/r/serpro69/ansible-debian                       |

Tags of images follow the same naming as the source images. E.g. for tags of `ansible-debian` see list of tags in the [docker official debian image](https://hub.docker.com/_/debian) repo.

## Build

```
docker build -f dockerfile-<os> -t <image-name> .
```

