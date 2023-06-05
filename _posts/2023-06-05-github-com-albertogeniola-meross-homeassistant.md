---
title: meross-homeassistant
categories: ['python', 'meross', 'homeassistant']
---
## [meross-homeassistant](https://github.com/albertogeniola/meross-homeassistant)

### Custom component that leverages the Meross IoT library to integrate with Homeassistant

In the past 24 hours, Meross has changed the signature of its HTTP API version (keeping the same API version in place). 
**That did break every HomeAssistant integration version below 1.2.6 (included).**
In order to solve the issue, you should upgrade to version **1.2.8** which includes the necessary changes to work again with the updated version of the Meross APIs.
