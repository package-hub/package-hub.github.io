---
title: fleet
categories: ['java']
---
## [fleet](https://github.com/linuxserver/fleet)

### Status and image fleet metadata management application for Docker images


Fleet is a Docker Hub repository and image management tool for organisations (or individuals) who wish to display a list of all currently available images, along with their latest version and build status. The idea for this application was borne out of a necessity for the LinuxServer team to be able to provide a mechanism for its users to see the current build version of the images they use.

Image information is retrieved via the Docker Hub API (v2) through a scheduled task, which runs at a given (configurable) interval. This task will synchronise all repositories owned by the user whose credentials are used to authorise the initial requests to Docker Hub. Fleet will store in memory a valid authorisation token and will reuse it until it expires, after which a new token will be requested.
