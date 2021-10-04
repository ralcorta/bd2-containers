# :rocket: BD2 - Docker Containers
## Docker config

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains a Docker Compose file with a configuration for setting up an environment with each configuration required.
<pre>
- We can do it
- We will do it
- We will cry doing it
- Jeff Bezos will cry if you don't approve it
- I'll cry if I don't approve
- ✨ Magic ✨
</pre>

## Features

- [Redis](https://redis.io)
- [Redis commander](https://github.com/joeferner/redis-commander)
- [Mongo](https://www.mongodb.com/)
- [Mongo Express](https://github.com/mongo-express/mongo-express)
<<<<<<< HEAD
- [Mongo GUI](https://github.com/arunbandari/mongo-gui)
- :rocket: &nbsp; More new features comming soon!
=======
- [Neo4J](https://neo4j.com)
- :rocket: &nbsp; More new features coming soon!
>>>>>>> 3d70c8a2b5516a360f29f8f83f340e22523fd1c1

##### Tips:
For testing apis: Mockaroo

## Pre-requisites

Required: [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/).
If you have Windows or Mac, you can install [Docker desktop](https://docs.docker.com/desktop/dashboard/)
| Operating System | Site URL|
| ------ | ------ |
| Mac | [https://docs.docker.com/docker-for-mac/install](https://docs.docker.com/docker-for-mac/install) |
| Windows | [https://docs.docker.com/docker-for-windows/install](https://docs.docker.com/docker-for-windows/install) |

If you are on a GNU / Linux distribution and you don't want to type all the commands to install dependencies, you can take a look at this [Gist](https://gist.github.com/EvgenyOrekhov/1ed8a4466efd0a59d73a11d753c0167b)

## Installation

Install dependencies and configure containers.

```sh
$ sudo docker-compose up -d
```
<pre>
[sudo] Run the process in Root mode.  
[docker-compose] The docker extension for managing multiple containers at the same time.  
[top] Docker composition parameter to download, create and configure containers.  
[-d] Create the process in the background. If you want to see the creation of the process and the console, you can remove this flag.  
</pre>
## Remove dockers

If you want to remove the containers created by the docker-compose command, you can type this:

```sh
$ sudo docker-compose down -v
```


## Docker Access

After starting the containers you will be able to access them throught their URL:PORT (like localhost:6379)

Aclaration: The ports are listened inside of environment file (.env). You can change it as you like.

<pre>

Redis: localhost:6379
Redis GUI (redis-commander): localhost:8081

----

Mongo: localhost:27017
Mongo GUI (mongo-express): localhost:8888
Mongo GUI (mongo-gui): localhost:4321



----

Neo4J: localhost:7474
Neo4J GUI: localhost:7687

</pre>

You can use those interfaces or download the one you like the most and access the main services.  
Tip: Internally, containers communicate via service names, not localhost.


## License

[MIT](LICENSE)

**Free Software, Hell Yeah!**
