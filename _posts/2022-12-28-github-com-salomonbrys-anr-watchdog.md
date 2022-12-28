---
title: ANR-WatchDog
categories: ['java']
---
## [ANR-WatchDog](https://github.com/SalomonBrys/ANR-WatchDog)

### A simple watchdog that detects Android ANR (Application Not Responding) error and throws a meaningful exception


1.  In the `app/build.gradle` file, add:

    ```
    implementation 'com.github.anrwatchdog:anrwatchdog:1.4.0'
    ```

2.  In your application class, in `onCreate`, add:

    ```java
    new ANRWatchDog().start();
    ```

