---
title: gc-opencommand-plugin
categories: ['java', 'grasscutter', 'grasscutter-plugin']
---
## [gc-opencommand-plugin](https://github.com/jie65535/gc-opencommand-plugin)

### A plugin that open the GC command execution interface for third-party clients


中文 | [English](README_en-US.md)

一个为第三方客户端开放GC命令执行接口的插件

自 `1.7.0` 起可以通过 `|` 或者换行来分隔多条命令，例如：
```shell
/a 1 | /a 2
/a 3
```

调用 `ping` 响应数据将包含插件版本号。
