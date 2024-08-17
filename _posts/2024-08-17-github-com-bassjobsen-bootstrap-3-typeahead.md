---
title: Bootstrap-3-Typeahead
categories: ['javascript']
---
## [Bootstrap-3-Typeahead](https://github.com/bassjobsen/Bootstrap-3-Typeahead)

### The Typeahead plugin from Twitter's Bootstrap 2 ready to use with Bootstrap 3 and Bootstrap 4


---

For simple autocomplete use cases there seems to be nothing wrong with the dropped typeahead plugin. Here you will find the typeahead autocomplete plugin for Twitter's Bootstrap 2 ready to use with Twitter's Bootstrap 3. The original code is written by [@mdo](http://twitter.com/mdo) and [@fat](http://twitter.com/fat).

Users who migrate their website or app from Twitter's Bootstrap 2 to Bootstrap 3 can also use this plugin to keep their current autocomplete functions. See for a complete list of migrations steps: [Migrate your templates from Twitter Bootstrap 2.x to Twitter Bootstrap 3](http://bassjobsen.weblogs.fm/migrate-your-templates-from-twitter-bootstrap-2-x-to-twitter-bootstrap-3/)

With Twitter Bootstrap 3 the typeahead plugin had been dropped. [@mdo](http://twitter.com/mdo) says: "in favor of folks using [Twitter's typeahead](https://github.com/twitter/typeahead.js). Twitter's typeahead has more features than the old bootstrap-typeahead.js and less bugs." Twitter's typeahead don't work direct with Bootstrap 3. The DOM structure of the dropdown menu used by `typeahead.js` differs from the DOM structure of the Bootstrap dropdown menu. You'll need to load some additional CSS in order to get the `typeahead.js` dropdown menu to fit the default Bootstrap theme. Try [extended Bootstrap LESS](https://github.com/bassjobsen/typeahead.js-bootstrap-css) or if your are looking for a more extended version try: [typeahead.js-bootstrap3.less](https://github.com/hyspace/typeahead.js-bootstrap3.less/blob/master/typeahead.less).

~~`Typeahead.js` doesn't seem ready for the new Twitter Bootstrap 3 at the moment. Code is not up to date and fixes are needed. See also:
[Typeahead problems with Bootstrap 3.0 RC1](http://stackoverflow.com/questions/18167246/typeahead-problems-with-bootstrap-3-0-rc1).~~
