---
title: UniFi-API-browser
categories: ['php', 'unifi', 'api-client']
---
## [UniFi-API-browser](https://github.com/Art-of-WiFi/UniFi-API-browser)

### Tool to browse data exposed by Ubiquiti's UniFi Controller API (demo: https://api-browser-demo.artofwifi.net/)


This tool is for browsing data that is exposed through Ubiquiti's UniFi Controller API, written in PHP, JavaScript and the [Bootstrap](http://getbootstrap.com/) CSS framework.

It comes bundled with a **PHP class for access to the UniFi Controller API**, which supports [more API endpoints](https://github.com/Art-of-WiFi/UniFi-API-client#methods-and-functions-supported) than the UniFi API browser tool does.

If you plan on creating your own PHP code to leverage the UniFi controller API, it is recommended to use the standalone version of the API client class which can be found here: https://github.com/Art-of-WiFi/UniFi-API-client

You will find examples and detailed instructions there.

Please keep the following in mind:

- the API browser tool doesn't support all available data collections/API endpoints, see the list below of those that are currently supported
- currently, versions 4.x.x, 5.x.x, and 6.0.x of the UniFi Controller software are supported (version 6.0.42 has been confirmed to work) as well as UniFi OS-based controllers (version 5.12.59 has been confirmed to work)
- when accessing UniFi OS-based controllers (e.g. UDM PRO) through this tool, please read the remarks below regarding UniFi OS support
- there is still work to be done to add/improve functionality and usability of this tool so suggestions/comments are welcome. Please use the GitHub [issue](https://github.com/Art-of-WiFi/UniFi-API-browser/issues) list or the Ubiquiti Community forums (https://community.ubnt.com/t5/UniFi-Wireless/UniFi-API-browser-tool-released/m-p/1392651) to share your ideas/questions.
- please read the Security Notice below before installing this tool!

