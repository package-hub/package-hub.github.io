---
title: TvAppRepo
categories: ['java', 'android-tv-apps', 'launcher-shortcuts']
---
## [TvAppRepo](https://github.com/ITVlab/TvAppRepo)

### An app repository of Android TV apps

An app repository of Android TV apps

In Android TV's stock launcher, all apps that appear must have the `LEANBACK_LAUNCHER` attribute and have a TV banner. While this helps
guarantee the app works on TVs, it can make it difficult for other apps to be launched. While it's not impossible, it's not as convenient as
having an icon on the homescreen.

Using a python script, tiny shortcut apps are generated and can be installed. They simply contain the face of a Leanback app. However, once
they're opened they simply redirect users to the intended app. It's a simple workaround.

This workaround has a few advantages. By not modifying the APK directly, it allows updates to continue through the Google Play Store.
In fact, the actual app isn't touched at all. These shortcuts could point to anything: a website, a specific shortcut in an app,
or basically any Intent.

The python script cannot be run in the app. The app contains several sideloading tools, including supporting #SIDELOADTAG, showing all your
downloaded apps, and browsing apps that have generated shortcuts. The app should also be able to notify users when it needs to be updated.
