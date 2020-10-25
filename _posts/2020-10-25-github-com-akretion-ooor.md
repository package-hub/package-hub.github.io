---
title: ooor
categories: ['ruby', 'odoo', 'rails']
---
## [ooor](https://github.com/akretion/ooor)

### Odoo Ruby JSON client. Emulates ActiveRecord enough (as much as Mongoid; Implements ActiveModel) to make Rails development with an Odoo datastore straightforward


Let's test ooor in an irb console (irb command):

```ruby
require 'rubygems'
require 'ooor'
Ooor.new(:url => 'http://localhost:8069/xmlrpc', :database => 'mybase', :username => 'admin', :password => 'admin')
```

This should load all your Odoo models into Ruby proxy Activeresource objects. Of course there are option to load only some models.
Let's try to retrieve the user with id 1:

```ruby
ResUsers.find(1)
```

(in case you have an error like "no such file to load -- net/https", then on Debian/Ubuntu, you might need to do before: apt-get install libopenssl-ruby)

