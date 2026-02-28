---
title: domdig
categories: ['javascript']
---
## [domdig](https://github.com/fcavallarin/domdig)

### DOM XSS scanner for Single Page Applications

DOMDig is a DOM XSS scanner that runs inside the Chromium web browser and it can scan single page applications (SPA) recursively.  
Unlike other scanners, DOMDig can crawl any webapplication (including gmail) by keeping track of DOM modifications and XHR/fetch/websocket requests and it can simulate a real user interaction by firing events. During this process, XSS payloads are put into input fields and their execution is tracked in order to find injection points and the related URL modifications.  
It is based on [htcrawl](https://htcrawl.org), a node library powerful enough to easily crawl a gmail account.

