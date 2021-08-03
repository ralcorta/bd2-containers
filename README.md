# BD2 - Docker Containers
## Docker config of BD2 UADE

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains a Docker Compose file with a configuration for setting up an environment with each configuration required.

- We can do it
- We will do it
- We will cry doing it
- Jef Besos will cry if you don't approve it
- I will cry if I don't approve it
- ✨Magic ✨

## Features

- [Redis](https://redis.io)
- [Redis commander](https://github.com/joeferner/redis-commander)
- ✨More new features comming soon!

##### Tips:
For testing apis: Mockaroo

## Pre-requisites

Required: [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/).
If you have Windows or Mac, you can install [Docker desktop](https://docs.docker.com/desktop/dashboard/)
| Operative System | Site URL|
| ------ | ------ |
| Mac | [https://docs.docker.com/docker-for-mac/install](https://docs.docker.com/docker-for-mac/install) |
| Windows | [https://docs.docker.com/docker-for-windows/install](https://docs.docker.com/docker-for-windows/install) |

## Installation

Install the dependencies and set up the containers.

```sh
$ sudo docker-compose up -d
```
[sudo] Run the process in Root mode.  
[docker-compose] The docker extension for managing multiple containers at the same time.  
[top] Docker composition parameter to download, create and configure containers.  
[-d] Create the process in the background. If you want to see the creation of the process and the console, you can remove this flag.  

## Remove dockers

If you want to remove the containers created by the docker-compose command, you can type this:

```sh
$ sudo docker-compose down -v
```


## Docker Access

After starting the containers you will be able to access them throught his URL:PORT (like localhost:6379)

```sh
Redis: localhost:6379
Redis GUI (redis-commander): localhost:8081
```

## License

MIT

**Free Software, Hell Yeah!**
