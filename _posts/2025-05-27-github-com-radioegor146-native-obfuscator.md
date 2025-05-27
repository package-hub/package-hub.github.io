---
title: native-obfuscator
categories: ['java', 'cpp', 'bytecode']
---
## [native-obfuscator](https://github.com/radioegor146/native-obfuscator)

### Java .class to .cpp converter for use with JNI

Java .class to .cpp converter for use with JNI

Currently fully supports only Java 8. Java 9+ and Android support is entirely experimental

Warning: blacklist/whitelist usage is recommended because this tool slows down code significantly (like do not obfuscate full Minecraft .jar)

Also, this tool does not particularly obfuscate your code; it just transpiles it to native. Remember to use protectors like VMProtect, Themida, or obfuscator-llvm (in case of clang usage)

---
