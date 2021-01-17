---
title: YUKI
categories: ['typescript', 'galgame', 'visual-novel']
---
## [YUKI](https://github.com/project-yuki/YUKI)

### YUKI Galgame Translator


2020.5.30 晚间，大量用户使用 YUKI 时遇到错误为`ERR: TypeError: Cannot read property 'target' of undefined`的报错窗口。经排查，该报错由彩云 API 目前严重的不稳定状态导致。现已紧急推送 v0.14.3，修复上述问题，但彩云 API 目前仍无法使用，因此请目前所有版本的 YUKI 用户关闭彩云 API（具体方法：打开 YUKI 根目录下的 config\config.json 文件，将 onlineApis 数组中 name = "彩云" 的对象的 enable 属性改为 false）。关闭后，即使不升级至 v0.14.3 也可解决报错问题。
