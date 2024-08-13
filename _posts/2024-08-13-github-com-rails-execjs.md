---
title: execjs
categories: ['ruby']
---
## [execjs](https://github.com/rails/execjs)

### Run JavaScript code from Ruby


If you'd like to use a specific runtime rather than the autodetected one, you can assign `ExecJS.runtime`:

```ruby
ExecJS.runtime = ExecJS::Runtimes::Node
```

Alternatively, you can define it via the `EXECJS_RUNTIME` environment variable:

```bash
EXECJS_RUNTIME=Node ruby ...
```

You can find the list of possible runtimes in [`lib/execjs/runtimes.rb`](https://github.com/rails/execjs/blob/master/lib/execjs/runtimes.rb).
