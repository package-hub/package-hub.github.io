---
title: bugsnag-js
categories: ['typescript', 'bugsnag', 'javascript']
---
## [bugsnag-js](https://github.com/bugsnag/bugsnag-js)

### Javascript error handling tool for Bugsnag. Monitor and report JavaScript bugs & errors.


Automatically detect JavaScript errors in the browser, Node.js, React Native and Expo, with plugins for React, Vue, Angular, Express, Restify and Koa. Get cross-platform error detection for handled and unhandled errors with real-time error alerts and detailed diagnostic reports.

Learn more about [JavaScript error reporting](https://www.bugsnag.com/platforms/javascript/) and [React Native error reporting](https://www.bugsnag.com/platforms/react-native-error-reporting/) from Bugsnag.

---

This is a monorepo (managed with [Lerna](https://lernajs.io/)) containing our universal error reporting client [`@bugsnag/js`](/packages/js), our Expo client [`@bugsnag/expo`](/packages/expo) and our React Native client [`@bugsnag/react-native`](/packages/react-native), along with:

- the core Bugsnag libraries for reporting errors ([`@bugsnag/core`](/packages/core))
- plugins for supporting various frameworks (e.g. [`@bugsnag/plugin-react`](/packages/plugin-react))
- plugins for internal functionality (e.g. [`@bugsnag/plugin-simple-throttle`](/packages/plugin-simple-throttle))

Etc. See [packages](/packages) for a full list of contents.
