---
title: turbo_tests
categories: ['ruby', 'rspec', 'parallel-tests']
---
## [turbo_tests](https://github.com/serpapi/turbo_tests)

### Run RSpec tests on multiple cores. Like parallel_tests but with incremental summarized output. Originally extracted from the Discourse and Rubygems source code.


`turbo_tests` is a drop-in replacement for [`grosser/parallel_tests`](https://github.com/grosser/parallel_tests) with incremental summarized output. Source code of this gem is based on [Discourse](https://github.com/discourse/discourse/blob/6b9784cf8a18636bce281a7e4d18e65a0cbc6290/lib/turbo_tests.rb) and [RubyGems](https://github.com/rubygems/rubygems/tree/390335ceb351668cd433bd5bb9823dd021f82533/bundler/tool) work in this area.

Incremental summarized output [doesn't fit vision of `parallel_tests` author](https://github.com/grosser/parallel_tests/issues/708) and [RSpec doesn't support built-in parallel testing yet](https://github.com/rspec/rspec-rails/issues/2104#issuecomment-658474900). This gem will not be useful once one of the issues above will be implemented.
