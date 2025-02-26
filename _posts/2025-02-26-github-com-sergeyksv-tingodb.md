---
title: tingodb
categories: ['javascript']
---
## [tingodb](https://github.com/sergeyksv/tingodb)

### Embedded Node.js database upward compatible with MongoDB


In contrast to MongoDB, the module `require` call will not return a usable module. It will return a function that accepts configuration options. This function will return something similar to the MongoDB module. The extra step allows for passing some options that will control database behavior.
