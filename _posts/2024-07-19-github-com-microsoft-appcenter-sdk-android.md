---
title: appcenter-sdk-android
categories: ['java', 'mobile-center', 'android']
---
## [appcenter-sdk-android](https://github.com/microsoft/appcenter-sdk-android)

### Development repository for the App Center SDK for Android


App Center is your continuous integration, delivery and learning solution for Android apps.
Get faster release cycles, higher-quality apps, and the insights to build what users want.

The App Center SDK uses a modular architecture so you can use any or all of the following services:

1. **App Center Analytics**: App Center Analytics helps you understand user behavior and customer engagement to improve your app. The SDK automatically captures session count, device properties like model, OS version, etc. You can define your own custom events to measure things that matter to you. All the information captured is available in the App Center portal for you to analyze the data.

2. **App Center Crashes**: App Center Crashes will automatically generate a crash log every time your app crashes. The log is first written to the device's storage and when the user starts the app again, the crash report will be sent to App Center. Collecting crashes works for both beta and live apps, i.e. those submitted to the App Store. Crash logs contain valuable information for you to help fix the crash.

3. **App Center Distribute**: App Center Distribute will let your users install a new version of the app when you distribute it via the App Center. With a new version of the app available, the SDK will present an update dialog to the users to either download or postpone the new version. Once they choose to update, the SDK will start to update your application.

    > **Google Play considers the in-app update code as malicious behavior even if it isn’t used at runtime. Please use App Center Distribute Play instead before submitting your app to Google Play. Failure to not remove the in-app update code can lead to noncompliance and removal of the app from Google Play.**
    > See [Remove in-app updates for Google Play builds](https://docs.microsoft.com/en-us/appcenter/sdk/distribute/android#remove-in-app-updates-for-google-play-builds) documentation for details.

4. **App Center Distribute Play**: App Center Distribute Play is stubbing the Distribute package's APIs to avoid Google Play rejecting the application for malicious behavior. It must be used only for build variants which are going to be published on Google Play.
