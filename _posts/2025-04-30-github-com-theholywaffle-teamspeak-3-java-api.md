---
title: TeamSpeak-3-Java-API
categories: ['java', 'teamspeak', 'teamspeak3']
---
## [TeamSpeak-3-Java-API](https://github.com/TheHolyWaffle/TeamSpeak-3-Java-API)

### A Java wrapper of TeamSpeak's 3 server query API.


- Contains almost all server query functionality! (see [TeamSpeak 3 Server Query Manual](https://www.teamspeak-info.de/downloads/ts3_serverquery_manual.pdf))
- Built-in keep alive method
- Threaded event-based system
- Both [synchronous](src/main/java/com/github/theholywaffle/teamspeak3/TS3Api.java) and [asynchronous](src/main/java/com/github/theholywaffle/teamspeak3/TS3ApiAsync.java) implementations available
- Can be set up to reconnect and automatically resume execution after a connection problem
- Utilizes [SLF4J](https://www.slf4j.org/) for logging abstraction and integrates with your logging configuration
