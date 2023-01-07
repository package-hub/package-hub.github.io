---
title: Obfuscapk
categories: ['python', 'android', 'application']
---
## [Obfuscapk](https://github.com/ClaudiuGeorgiu/Obfuscapk)

### An automatic obfuscation tool for Android apps that works in a black-box fashion, supports advanced obfuscation features and has a modular architecture easily extensible with new techniques


Obfuscapk is adding support for
[Android App Bundles](https://developer.android.com/guide/app-bundle) (aab files) by
using [BundleDecompiler](https://github.com/TamilanPeriyasamy/BundleDecompiler) (see
[#121](https://github.com/ClaudiuGeorgiu/Obfuscapk/pull/121)). In order to use this new
feature, download the latest version of BundleDecompiler available from
[here](https://github.com/TamilanPeriyasamy/BundleDecompiler/tree/master/build/libs),
save it as `BundleDecompiler.jar` in a directory included in `PATH` (e.g., in Ubuntu,
`/usr/local/bin` or `/usr/bin`) and make sure it has the executable flag set.

`NOTE:` BundleDecompiler doesn't work on Windows yet, so app bundle obfuscation is not
supported by Obfuscapk on Windows platform. Also, app bundle support is still in early
development, so if you faced any problems or if you want to help us improve, please see
[contributing](#-contributing).


