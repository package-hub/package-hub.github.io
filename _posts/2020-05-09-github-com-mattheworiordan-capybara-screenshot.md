---
title: capybara-screenshot
categories: ['ruby']
---
## [capybara-screenshot](https://github.com/mattheworiordan/capybara-screenshot)

### Automatically save screen shots when a Capybara scenario fails


`capybara-screenshot` used with [Capybara](https://github.com/jnicklas/capybara) alongside [Cucumber](http://cukes.info/), [Rspec](https://www.relishapp.com/rspec) or [Minitest](https://github.com/seattlerb/minitest), will capture a screenshot for each failure in your test suite. Associated screenshot and HTML file
of the failed page (when using [capybara-webkit](https://github.com/thoughtbot/capybara-webkit), [Selenium](http://seleniumhq.org/) or [poltergeist](https://github.com/jonleighton/poltergeist)) is saved into `$APPLICATION_ROOT/tmp/capybara`.