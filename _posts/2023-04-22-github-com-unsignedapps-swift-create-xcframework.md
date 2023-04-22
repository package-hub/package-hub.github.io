---
title: swift-create-xcframework
categories: ['javascript']
---
## [swift-create-xcframework](https://github.com/unsignedapps/swift-create-xcframework)

### A simple Command Line Tool to create XCFrameworks by wrapping xcodebuild.


swift-create-xcframework is a very simple tool designed to wrap `xcodebuild` and the process of creating multiple frameworks for a Swift Package and merging them into a single XCFramework.

On the 23rd of June 2020, Apple announced Xcode 12 and Swift 5.3 with support for Binary Targets. Though they provide a simplified way to [include Binary Frameworks in your packages][apple-docs], they did not provide a simple way to create your XCFrameworks, with only some [documentation for the long manual process][manual-docs]. swift-create-xcframework bridges that gap.

**Note:** swift-create-xcframework pre-dates the WWDC20 announcement and is tested with Xcode 11.4 or later, but should work with Xcode 11.2 or later. You can include the generated XCFrameworks in your app manually even without Xcode 12.
