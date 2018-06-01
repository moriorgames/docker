Base Docker Repository
======================

Base docker repository to build images with intermediate container and be more efficient when creating containers.

I Have a base repository for php72.

```
$ cd php72
$ docker build -t moriorgames/php72-base .
$ docker tag moriorgames/php72-base moriorgames/php72-base:latest
$ docker login
$ docker push moriorgames/php72-base
```
