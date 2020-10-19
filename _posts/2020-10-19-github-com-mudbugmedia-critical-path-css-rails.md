---
title: critical-path-css-rails
categories: ['ruby', 'css-path', 'css-generator']
---
## [critical-path-css-rails](https://github.com/mudbugmedia/critical-path-css-rails)

### Only load the CSS you need for the initial viewport in Rails!


Only load the CSS you need for the initial viewport in Rails!

This gem gives you the ability to load only the CSS you *need* on an initial page view. This gives you blazin' fast rending as there's no initial network call to grab your application's CSS.

This gem assumes that you'll load the rest of the CSS asyncronously. At the moment, the suggested way is to use the [loadcss-rails](https://github.com/michael-misshore/loadcss-rails) gem.

This gem uses [Penthouse](https://github.com/pocketjoso/penthouse) to generate the critical CSS.
