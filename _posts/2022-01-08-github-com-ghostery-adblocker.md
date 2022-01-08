---
title: adblocker
categories: ['typescript', 'content-blocking', 'javascript']
---
## [adblocker](https://github.com/ghostery/adblocker)

### Efficient embeddable adblocker library


Cliqz' adblocker is the easiest and most efficient way to block ads and trackers in your project. Only a few lines of code are required to integrate smoothly with [Puppeteer](https://github.com/cliqz-oss/adblocker/tree/master/packages/adblocker-puppeteer-example), [Electron](https://github.com/cliqz-oss/adblocker/tree/master/packages/adblocker-electron-example), a  Chrome- and Firefox-compatible [browser extension](https://github.com/cliqz-oss/adblocker/tree/master/packages/adblocker-webextension-example), or any environment supporting [JavaScript](https://github.com/cliqz-oss/adblocker/tree/master/packages/adblocker) (e.g. Node.js or React Native).

Here is how to do it in two steps for a Chrome- and Firefox-compatible WebExtension:
1. Install: `npm install --save @cliqz/adblocker-webextension`
2. Add the following in your background script:
```js
import { WebExtensionBlocker } from '@cliqz/adblocker-webextension';

WebExtensionBlocker.fromPrebuiltAdsAndTracking().then((blocker) => {
  blocker.enableBlockingInBrowser(browser);
});
```

Congratulations, you are now blocking all ads and trackers! :tada:
