---
title: request_store
categories: ['ruby']
---
## [request_store](https://github.com/steveklabnik/request_store)

### Per-request global storage for Rack.


Ever needed to use a global variable in Rails? Ugh, that's the worst. If you
need global state, you've probably reached for `Thread.current`. Like this:

```ruby
def self.foo
  Thread.current[:foo] ||= 0
end

def self.foo=(value)
  Thread.current[:foo] = value
end
```

Ugh! I hate it. But you gotta do what you gotta do...
