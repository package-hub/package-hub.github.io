---
title: critters
categories: ['javascript', 'webpack', 'webpack-plugin']
---
## [critters](https://github.com/GoogleChromeLabs/critters)

### 🦔 A Webpack plugin to inline your critical CSS and lazy-load the rest.


It's a little different from [other options](#similar-libraries), because it **doesn't use a headless browser** to render content.  This tradeoff allows Critters to be very **fast and lightweight**. It also means Critters inlines all CSS rules used by your document, rather than only those needed for above-the-fold content. For alternatives, see [Similar Libraries](#similar-libraries).

Critters' design makes it a good fit when inlining critical CSS for prerendered/SSR'd Single Page Applications. It was developed to be an excellent compliment to [prerender-loader](https://github.com/GoogleChromeLabs/prerender-loader), combining to dramatically improve first paint time for most Single Page Applications.
