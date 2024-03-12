---
title: Selenium-Grid-Extras
categories: ['ruby']
---
## [Selenium-Grid-Extras](https://github.com/groupon/Selenium-Grid-Extras)

### Simplify the management of the Selenium Grid Nodes and stabilize said nodes by cleaning up the test environment after the build has been completed


1. In the terminal run following command:
```bash
java -jar Selenium-Grid-Extras-Jar.jar
```

2. You will be prompted with several questions, first one will ask you if you want to set this computer as a HUB, Node, or both. Answer 2 for HUB

3. Leave the Host name for Grid Hub as default 127.0.0.1

4. Set port to be used by Selenium Grid Hub, default is 4444

5. You will be asked if you wish to auto update Selenium. If you answer yes, then every time Selenium Grid Extras is started it will check fo the latest version of Selenium Stand Alone Server, IEDriver, and ChromeDriver. If you choose to not auto update, you will be asked what versions of each driver to lock into.

