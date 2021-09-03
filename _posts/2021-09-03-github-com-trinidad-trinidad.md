---
title: trinidad
categories: ['ruby']
---
## [trinidad](https://github.com/trinidad/trinidad)

### Web server for Rails/Rack applications built upon JRuby::Rack and Apache Tomcat


Trinidad allows you to run Rails and/or Rack applications within an embedded
Tomcat container. Apache Tomcat (formerly also Jakarta Tomcat) is an open source
web server and Servlet container with a long history that dates back to the
previous millenia.

Trinidad's goals with bringing Tomcat into JRuby land are mostly the following :

- **flexibility** especially in terms of configuration it allows you to tune
  (almost) everything from a simple *trinidad.yml* (or .rb) configuration file
- **portability** there's no vendor lock-in as we use `JRuby::Rack`, thus even
  if you do some Java integration or use it's Rack Servlet extensions you're
  still able to migrate to a standalone Tomcat or any other Servlet container
- easy Java integration (just in-case you need it, it's there)
- **extensions** such as connection pooling (sharing pools between deployed
  Rails apps) and (threaded) worker adapters for `Resque` and `Delayed::Job`
