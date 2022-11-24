---
title: sail
categories: ['ruby', 'rails', 'settings']
---
## [sail](https://github.com/vinistock/sail)

### Sail is a lightweight Rails engine that brings an admin panel for managing configuration settings on a live Rails app


This Rails engine brings a setting model into your app to be used as feature flags, gauges, knobs and other live controls you may need.

It saves configurations to the database so that they can be changed while the application is running, without requiring a deploy.

Having this ability enables live experiments and tuning to find an application's best setup.

Enable/Disable a new feature, turn ON/OFF ab testing for new functionality, change jobs' parameters to tune performance, you name it.

It comes with a lightweight responsive admin dashboard for searching and changing configurations on the fly.

Sail assigns to each setting a _relevancy score_. This metric is calculated while the application is running and is based on the relative number of times a setting is invoked and on the total number of settings. The goal is to have an indicator of how critical changing a setting's value can be based on its frequency of usage.
