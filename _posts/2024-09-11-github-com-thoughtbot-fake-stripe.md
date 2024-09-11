---
title: fake_stripe
categories: ['ruby']
---
## [fake_stripe](https://github.com/thoughtbot/fake_stripe)

### A Stripe fake so that you can avoid hitting Stripe servers in tests.


This library is a way to test [Stripe](http://www.stripe.com/) code without hitting Stripe's
servers. It uses
[Capybara::Server](https://github.com/jnicklas/capybara/blob/master/lib/capybara/server.rb)
and [Webmock](https://github.com/bblimke/webmock) to intercept all of the calls from Stripe's
Ruby library and returns JSON that the Stripe library can parse.
