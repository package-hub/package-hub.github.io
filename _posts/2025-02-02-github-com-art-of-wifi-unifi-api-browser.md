---
title: UniFi-API-browser
categories: ['php', 'unifi', 'api-client']
---
## [UniFi-API-browser](https://github.com/Art-of-WiFi/UniFi-API-browser)

### Tool to browse data exposed by Ubiquiti's UniFi Controller API


This tool allows you to browse data exposed through the UniFi Controller API, developed using PHP, JavaScript,
and the [Bootstrap](http://getbootstrap.com/) CSS framework. It comes bundled with a **PHP class for access to the UniFi Controller API**, 
which supports [more API endpoints](https://github.com/Art-of-WiFi/UniFi-API-client#functionsmethods-supported) than the UniFi API browser tool.

If you plan on creating your own PHP code to interact with the UniFi controller API, it is recommended to use the
standalone version of the API client class, which can be found at https://github.com/Art-of-WiFi/UniFi-API-client.
There, you will also find examples and detailed instructions on how to use it.

Please keep the following in mind when using the UniFi API browser:

- The tool does not support all available data collections and API endpoints. See the list below for those currently supported.
- Currently, versions 5.X.X, 6.X.X, 7.X.X, and 8.X.X of the UniFi Controller software are supported (version **8.5.60** has been confirmed to work)
- The Network Application on UniFi OS-based controllers is also supported, same versions as above
- When accessing UniFi OS-based controllers through this tool, please read the remarks regarding UniFi OS support
- Please read the Security Notice before installing this tool.

