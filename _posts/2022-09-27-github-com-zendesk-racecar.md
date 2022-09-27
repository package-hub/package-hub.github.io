---
title: racecar
categories: ['ruby', 'rails', 'kafka']
---
## [racecar](https://github.com/zendesk/racecar)

### Racecar: a simple framework for Kafka consumers in Ruby


Racecar is a friendly and easy-to-approach Kafka consumer framework. It allows you to write small applications that process messages stored in Kafka topics while optionally integrating with your Rails models.

The framework is based on [rdkafka-ruby](https://github.com/appsignal/rdkafka-ruby), which, when used directly, can be a challenge: it's a flexible library with lots of knobs and options. Most users don't need that level of flexibility, though. Racecar provides a simple and intuitive way to build and configure Kafka consumers.

**NOTE:** Racecar requires Kafka 0.10 or higher.
