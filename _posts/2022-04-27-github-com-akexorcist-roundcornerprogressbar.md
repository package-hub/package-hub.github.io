---
title: RoundCornerProgressBar
categories: ['java', 'kotlin', 'android']
---
## [RoundCornerProgressBar](https://github.com/akexorcist/RoundCornerProgressBar)

### [Android] Round Corner Progress Bar Library for Android

Change the view ID parameter in `onProgressChanged` to View class
```kotlin
// Old
fun onProgressChanged(
    viewId: Int, 
    progress: Float, 
    isPrimaryProgress: Boolean, 
    isSecondaryProgress: Boolean
)

// New
fun onProgressChanged(
    view: View, 
    progress: Float, 
    isPrimaryProgress: Boolean, 
    isSecondaryProgress: Boolean
)
```
