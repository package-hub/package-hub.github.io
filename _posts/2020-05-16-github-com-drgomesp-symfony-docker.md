---
title: symfony-docker
categories: ['php', 'symfony-docker', 'symfony']
---
## [symfony-docker](https://github.com/drgomesp/symfony-docker)

### :whale: The Symfony Docker Edition – featuring PHP 7, Docker and Docker Compose


> Before anything, you need to make sure you have Docker properly setup in your environment. For that, refer to the official documentation for both [Docker](https://docs.docker.com/) and [Docker Compose](https://docs.docker.com/compose/). Also, if you're developing on Mac or Windows – *yeah, maybe that's the case* –, make sure you have [Docker Machine](https://docs.docker.com/machine/) properly setup.

> This project depends on having [jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy) running. This is a reverse proxy container that will allow having multiple projects running on port 80.

Build and run the containers:

```bash
docker-compose up -d --build
```

Once that's done, you should be able to access the application on the IP that docker (or Docker Machine) is running at.
