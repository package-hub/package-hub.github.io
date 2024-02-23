---
title: capybara-screenshot
categories: ['ruby']
---
## [capybara-screenshot](https://github.com/mattheworiordan/capybara-screenshot)

### Automatically save screen shots when a Capybara scenario fails


`capybara-screenshot` used with [Capybara](https://github.com/jnicklas/capybara) alongside [Cucumber](http://cukes.info/), [Rspec](https://www.relishapp.com/rspec) or [Minitest](https://github.com/seattlerb/minitest), will capture a screenshot for each failure in your test suite. Associated screenshot and HTML file
of the failed page (when using [capybara-webkit](https://github.com/thoughtbot/capybara-webkit), [Selenium](http://seleniumhq.org/), [poltergeist](https://github.com/jonleighton/poltergeist) or [cuprite](https://github.com/machinio/cuprite)) is saved into `$APPLICATION_ROOT/tmp/capybara`.

Available screenshots for each test failure is incredibly helpful for diagnosing problems quickly in your failing steps. You have the ability to view screenshots (when applicable) and source code at the time of each failure.

_Please note that Ruby 1.9+ is required to use this Gem. For Ruby 1.8 support, please see the [capybara-screenshot Ruby 1.8 branch](https://github.com/mattheworiordan/capybara-screenshot/tree/ruby-1.8-support)_

Installation
-----
