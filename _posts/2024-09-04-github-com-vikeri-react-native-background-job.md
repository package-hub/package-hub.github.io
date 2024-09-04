---
title: react-native-background-job
categories: ['java', 'react-native', 'scheduled-jobs']
---
## [react-native-background-job](https://github.com/vikeri/react-native-background-job)

### Schedule background jobs in React Native that run your JavaScript when your app is in the background/killed.


Schedule background jobs that run your JavaScript when your app is in the background or if you feel brave even in foreground.

The jobs will run even if the app has been closed and, by default, also persists over restarts.

This library relies on React Native's [`HeadlessJS`](https://facebook.github.io/react-native/docs/headless-js-android.html) which is currently only supported on Android.

On the native side it uses either [`Firebase JobDispatcher`](https://github.com/firebase/firebase-jobdispatcher-android) or a [`AlarmManager`](https://developer.android.com/reference/android/app/AlarmManager.html).

-   Firebase JobDispatcher (default): The jobs can't be scheduled exactly and depending on the Android API version different `period` time is allowed. `FirebaseJobDispatcher` is the most battery efficient backward compatible way of scheduling background tasks. 

-   AlarmManager by setting `exact` to `true`: Simple propriatery implementation that is only ment to be used while testing. It only cares about executing on time, all other parameters are ignored - job is not persisted on reboot.
