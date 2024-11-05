---
title: optica
categories: ['ruby']
---
## [optica](https://github.com/airbnb/optica)

### A tool for keeping track of nodes in your infrastructure


Optica is a service for registering and locating nodes.
It provides a simple REST API.

Nodes can POST to / to register themselves with some parameters.
Humans can GET / to get a list of all registered nodes.
GET also accepts some parameters to limit which of the registered nodes you see.
