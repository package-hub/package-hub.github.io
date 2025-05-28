---
title: rspec-retry
categories: ['ruby']
---
## [rspec-retry](https://github.com/NoRedInk/rspec-retry)

### retry randomly failing rspec example


RSpec::Retry adds a ``:retry`` option for intermittently failing rspec examples.
If an example has the ``:retry`` option, rspec will retry the example the
specified number of times until the example succeeds.
