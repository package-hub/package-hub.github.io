---
title: docker-plugin
categories: ['java', 'docker', 'cloud']
---
## [docker-plugin](https://github.com/jenkinsci/docker-plugin)

### Jenkins cloud plugin that uses Docker


This plugin allows containers to be dynamically provisioned as Jenkins agents using Docker.
It is a Jenkins Cloud plugin for Docker.

This plugin allows a [Docker](https://docs.docker.com/) host to dynamically provision a container as a Jenkins agent node,
lets that run a single build,
then removes that node,
without the build process or Jenkins job definition
requiring any awareness of Docker.

The Jenkins administrator configures Jenkins with
Docker hosts,
one or more "templates"
that describe
the labels/tags provided by the template,
the Docker image,
and Jenkins creates agents on-demand using those Docker containers.
