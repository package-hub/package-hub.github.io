---
title: simple_token_authentication
categories: ['ruby', 'devise', 'authentication']
---
## [simple_token_authentication](https://github.com/gonzalo-bulnes/simple_token_authentication)

### Simple (but safe) token authentication for Rails apps or API with Devise.


First install [Devise][devise] and configure it with any modules you want, then add the gem to your `Gemfile` and `bundle install`:

```ruby
# Gemfile

gem 'simple_token_authentication', '~> 1.0' # see semver.org
```

Once that done, only two steps are required to setup token authentication:

1. [Make one or more models token authenticatable][token_authenticatable] (ActiveRecord and Mongoid are supported)
1. [Allow controllers to handle token authentication][token_authentication_handler] (Rails, Rails API, and `ActionController::Metal` are supported)

_If you want more details about how the gem works, keep reading! We'll get to these two steps after the overview._

  [token_authenticatable]: #make-models-token-authenticatable
  [token_authentication_handler]: #allow-controllers-to-handle-token-authentication
