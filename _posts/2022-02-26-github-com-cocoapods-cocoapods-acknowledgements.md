---
title: cocoapods-acknowledgements
categories: ['ruby']
---
## [cocoapods-acknowledgements](https://github.com/CocoaPods/cocoapods-acknowledgements)

### CocoaPods plugin that generates a plist which includes the installation metadata


A CocoaPods plugin that generates a plist which includes the installation metadata. It supports generating two styles of dependency information.

* **Settings.bundle compatible plist** - This format is supported by a [large amount of pods](https://cocoapods.org/?q=acknow) and works with Apple's Settings.app.

* **Full Podspec metadata plist** - This format provides more information to the app allowing for deeper introspection, currently only [CPDAcknowledgements](https://github.com/cocoapods/CPDAcknowledgements) works with this format.
