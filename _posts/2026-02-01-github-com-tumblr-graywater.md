---
title: Graywater
categories: ['java', 'android', 'android-library']
---
## [Graywater](https://github.com/tumblr/Graywater)

### An Android library for decomposing RecyclerView layouts to improve scroll performance.


Graywater is a [`RecyclerView`](https://developer.android.com/reference/android/support/v7/widget/RecyclerView.html) adapter that facilitates the performant decomposition of complex and varied list items. It does this by mapping large data models to multiple viewholders, splitting the work needed to create a complex list item over multiple frames.

The concept is based off of [Facebook's post on a faster news feed](https://code.facebook.com/posts/879498888759525/fast-rendering-news-feed-on-android/) and [Components for Android](https://code.facebook.com/posts/531104390396423/components-for-android-a-declarative-framework-for-efficient-uis/), which have been realized as [Litho](http://fblitho.com).

Tumblr developed Graywater to improve scroll performance, reduce memory usage, and lay the foundation for a more modular codebase.

The name "Graywater" comes from [the process of recycling water](https://en.wikipedia.org/wiki/Greywater).

* [What is it?](#what-is-it)
* [How do you use it?](#how-do-you-use-it)
* [How does it work?](#how-does-it-work)
* [Other features](#other-features)
* [An addendum on binders and generics](#an-addendum-on-binders-and-generics)
