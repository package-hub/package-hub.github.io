---
title: rails-dom-testing
categories: ['ruby']
---
## [rails-dom-testing](https://github.com/rails/rails-dom-testing)

### Extracting DomAssertions and SelectorAssertions from ActionView.


This gem is responsible for comparing HTML doms and asserting that DOM elements are present in Rails applications.
Doms are compared via `assert_dom_equal` and `assert_dom_not_equal`.
Elements are asserted via `assert_dom`, `assert_dom_encoded`, `assert_dom_email` and a subset of the dom can be selected with `css_select`.
The gem is developed for Rails 4.2 and above, and will not work on previous versions.
