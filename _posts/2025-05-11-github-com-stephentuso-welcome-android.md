---
title: welcome-android
categories: ['java', 'android-library', 'android-ui']
---
## [welcome-android](https://github.com/stephentuso/welcome-android)

### A customizable welcome screen


If you want to use a button in a custom fragment instead of the default done button, call `useCustomDoneButton(true)` on the builder and `new WelcomeFinisher(MyFragment.this).finish()` in the button's `OnClickListener`.

Bottom Layouts
==============

The layout shown beneath the pages can be changed with the `bottomLayout` Builder method, which uses the `WelcomeConfiguration.BottomLayout` enum. The possible values are explained below.
