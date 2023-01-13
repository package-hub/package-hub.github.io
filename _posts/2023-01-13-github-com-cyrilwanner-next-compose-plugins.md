---
title: next-compose-plugins
categories: ['javascript', 'nextjs', 'plugin']
---
## [next-compose-plugins](https://github.com/cyrilwanner/next-compose-plugins)

### 💡next-compose-plugins provides a cleaner API for enabling and configuring plugins for next.js


Provides a cleaner API for enabling and configuring plugins for [next.js](https://github.com/zeit/next.js) because the default way next.js suggests to enable and configure plugins can get unclear and confusing when you have many plugins.

It is often unclear which plugins are enabled or which configuration belongs to which plugin because they are nested and share one configuration object.
This can also lead to orphaned configuration values when updating or removing plugins.

While `next-compose-plugins` tries to eliminate this case by providing an alternative API for enabling and configuring plugins where each plugin has their own configuration object, it also adds more features like phase specific plugins and configuration.
