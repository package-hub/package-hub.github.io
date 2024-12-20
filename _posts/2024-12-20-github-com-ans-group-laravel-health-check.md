---
title: laravel-health-check
categories: ['php', 'laravel-health-check', 'laravel']
---
## [laravel-health-check](https://github.com/ans-group/laravel-health-check)

### A package for checking the health of your Laravel & Lumen applications


The purpose of this package is to surface a health-check endpoint on `/health` which, when hit, returns the status of all the services and dependencies your project relies on, along with the overall health of your system. This is useful in both development and production for debugging issues with a faulty application.

This package also adds a `/ping` endpoint. Just hit `/ping` and receive `pong` in response. 

