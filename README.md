# Docker Node MongoDB Example

> Simple example of a dockerized Node/Mongo app

![Image](https://i.ibb.co/4Fgt31L/demo.gif)

## Quick Start

```bash
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build
```
after start that we can see the application running in our ipv4 address.

![image](https://user-images.githubusercontent.com/16930936/143658917-a9a1bcc2-a9c4-4025-a50e-f639d9ec0300.png)
