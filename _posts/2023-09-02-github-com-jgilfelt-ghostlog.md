---
title: GhostLog
categories: ['java']
---
## [GhostLog](https://github.com/jgilfelt/GhostLog)

### Android app that displays the logcat buffer in a system overlay window


If you are using the Gradle build system, simply add the following dependency in your `build.gradle` file:

```groovy
dependencies {
    debugCompile 'com.readystatesoftware.ghostlog:ghostlog-integration:+@aar'
}
```

Using `debugCompile` (recommended) ensures the integration library is never compiled into a release build.
