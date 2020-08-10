# Test-toolkit

![GitHub](https://img.shields.io/github/license/ttmo-ms/test-toolkit)
[![Github](https://img.shields.io/badge/orginzation_project-TTMO_MS-brightgreen)](https://www.github.com/ttmo-ms)
[![Github](https://img.shields.io/badge/author-Jover_Zhang-brightgreen)](https://www.joverzhang.com)

This project mainly provides testing environment or service for parent project [ttmo-ms](https://www.github.com/ttmo-ms).

# Contents

## listen-dog

[![Docker Pulls](https://img.shields.io/docker/pulls/ttmo/listen-dog?logo=docker)](https://hub.docker.com/repository/docker/ttmo/listen-dog)
[![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/ttmo/listen-dog?logo=docker)](https://hub.docker.com/repository/docker/ttmo/listen-dog)



### Support tags

- ![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/_/openjdk/8?label=openjdk&logo=java)
- ![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/_/openjdk/11?label=openjdk&logo=java)
- ![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/_/openjdk/15?label=openjdk&logo=java)

Pull from docker hub with:
```shell script
docker pull listen-dog:11
```

Customize build with:
```shell script
docker build -f openjdk/v11/Dockerfile -t listen-dog:11 ./listen-dog/
```
