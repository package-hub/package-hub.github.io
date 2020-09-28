---
title: acts_as_tenant
categories: ['ruby']
---
## [acts_as_tenant](https://github.com/ErwinM/acts_as_tenant)

### Easy multi-tenancy for Rails in a shared database setup.


```ruby
class ApplicationController < ActionController::Base
  set_current_tenant_by_subdomain(:account, :subdomain)
end
```

This tells acts_as_tenant to use the current subdomain to identify the current tenant. In addition, it tells acts_as_tenant that tenants are represented by the Account model and this model has a column named 'subdomain' which can be used to lookup the Account using the actual subdomain. If ommitted, the parameters will default to the values used above.

Alternatively, you could locate the tenant using the method `set_current_tenant_by_subdomain_or_domain( :account, :subdomain,  :domain )` which will try to match a record first by subdomain. in case it fails, by domain.
