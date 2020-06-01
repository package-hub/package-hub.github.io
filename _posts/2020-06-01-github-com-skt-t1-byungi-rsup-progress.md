---
title: rsup-progress
categories: ['typescript', 'progress-bar', 'progressbar']
---
## [rsup-progress](https://github.com/skt-t1-byungi/rsup-progress)

### ❤️ A simple progress bar with promises support

Example using `start`, `end` method.
```js
progress.start()

fetch('/data.json').then(response => {
    progress.end()
})
```

Using `promise` method.
```js
const response = await progress.promise(fetch('/data.json'))
```
