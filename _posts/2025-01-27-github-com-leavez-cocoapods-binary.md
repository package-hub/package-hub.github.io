---
title: cocoapods-binary
categories: ['ruby', 'cocoapods-plugin', 'compile-time']
---
## [cocoapods-binary](https://github.com/leavez/cocoapods-binary)

### integrate pods in form of prebuilt frameworks conveniently, reducing compile time


You may wonder why CocoaPods doesn't have a function to integrate libs in form of binaries, if there are dozens or hundreds of pods in your podfile and compile them for a great many times meaninglessly. Too many source code of libs slow down your compile and the response of IDE (e.g. code completion), and then reduce work efficiency, leaving us time to think about the meaning of life.

This plugin implements this simple wish. Replace the source code in pod target with prebuilt frameworks.

Why don't use Carthage? While Carthage also integrates libs in form of frameworks, there several reasons to use CocoaPods with this plugin:

- Pod is a good simple form to organize files, manage dependencies. (private or local pods)
- Fast switch between source code and binary, or partial source code, partial binaries.
- Some libs don't support Carthage.
