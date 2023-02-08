---
title: Log4j2Scan
categories: ['java']
---
## [Log4j2Scan](https://github.com/whwlsfb/Log4j2Scan)

### Log4j2 RCE Passive Scanner plugin for BurpSuite


> This tool is only for learning, research and self-examination. It should not be used for illegal purposes. All risks arising from the use of this tool have nothing to do with me!

> dnslog.cn is unable to access the interface from time to time due to the number of requests. If you are unable to scan, please try change dnslog platform from UI.

English | [简体中文](./README-zh_CN.md)

Log4j2 Remote Code Execution Vulnerability, Passive Scan Plugin for BurpSuite.

Support accurate hint vulnerability parameters, vulnerability location, support multi-dnslog platform extension, automatic ignore static files.

Vulnerability detection only supports the following types for now
- Url
- Cookie
- Header
- Body(x-www-form-urlencoded, json, xml, multipart)

