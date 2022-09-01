---
title: arturo
categories: ['ruby']
---
## [arturo](https://github.com/zendesk/arturo)

### Feature Sliders for Rails


Arturo provides feature sliders for Rails. It lets you turn features on and off
just like
[feature flippers](https://code.flickr.net/2009/12/02/flipping-out/),
but offers more fine-grained control. It supports deploying features only for
a given percentage of your users and whitelisting and blacklisting users based
on any criteria you can express in Ruby.

The selection is deterministic. So if a user has a feature on Monday, the
user will still have it on Tuesday (unless you *decrease* the feature's
deployment percentage or change its white- or blacklist settings).
