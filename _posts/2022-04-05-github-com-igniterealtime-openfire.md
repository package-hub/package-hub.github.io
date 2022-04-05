---
title: Openfire
categories: ['java', 'openfire', 'xmpp']
---
## [Openfire](https://github.com/igniterealtime/Openfire)

### An XMPP server licensed under the Open Source Apache License.


1. Run -> Edit Configurations... -> Add Application
2. fill in following values
    1. Name: Openfire
    2. Use classpath of module: starter
    3. Main class: org.jivesoftware.openfire.starter.ServerStarter
    4. VM options (adapt accordingly):
        ````
        -DopenfireHome="-absolute path to your project folder-\distribution\target\distribution-base" 
        -Xverify:none
        -server
        -Dlog4j.configurationFile="-absolute path to your project folder-\distribution\target\distribution-base\lib\log4j2.xml"
        -Dopenfire.lib.dir="-absolute path to your project folder-\distribution\target\distribution-base\lib"
        -Dfile.encoding=UTF-8
       ````
   5. Working directory: -absolute path to your project folder-
3. apply

You need to execute `mvnw verify` before you can launch openfire.
