---
title: ManifestEditor
categories: ['java']
---
## [ManifestEditor](https://github.com/WindySha/ManifestEditor)

### This is a tool used to modify Android Manifest binary file.

This is a tool used to modify Android Manifest binary file.  
此工具用于修改AndroidManifest二进制文件。比如，更改Manifest文件中的app包名，版本号，更改或新增app入口Application的类名，更改或新增debuggable的属性，增加usesPermission标签，增加meta-data标签等。
同时，为了更方便使用，提供了直接修改Apk包中的Manifest文件，并对修改后的Apk进行签名的功能。

比较常见的修改AndroidManifest二进制文件的工具，大致有:[apkeditor](https://github.com/8enet/apkeditor)和[AXMLEditor](https://github.com/fourbrother/AXMLEditor)

但是，这些工具都有一个相同的问题: 新增属性无法被Android系统解析出来。  
比如，在application标签下增加debuggable=true属性，安装后的App并不是debuggable的。

本工具并不存在此问题。当然，本工具可能存在其他一些问题，并未作充分测试。

此项目基于[axml](https://github.com/Sable/axml)，并在其基础做了二次封装和一些优化，使用起来更加方便。

This tool is used in project [Xpatch](https://github.com/WindySha/Xpatch)