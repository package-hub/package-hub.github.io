---
title: jndiat
categories: ['java']
---
## [jndiat](https://github.com/quentinhardy/jndiat)

### JNDI Attacking Tool


**JNDIAT** (**JNDI** **A**ttacking **T**ool) is an open source penetration testing tool that tests the security of **Weblogic** servers **through T3 protocol**.

Usage examples of JNDIAT:
* You want to search if there are Weblogic **ports which are accessible through T3 protocol**, over SSL/TLS or not;
* You want to **search valid accounts** remotely in order to have a privileged connection;
* You want to list **JNDIs (Java Naming and Directory Interface) which are accessible** to know what you can do on the remote Weblogic server (without or with a Weblogic account);
* You want to **use a unprotected (i.e. 'public') JDBC datasource** in order to get a remote interactive SQL shell;
* You want to **deploy an application** (e.g. War) on the Weblogic server in order to have a Web shell (account required).

Tested on Oracle Weblogic 12 and Java JRE 8 ([Official Download Link](https://www.java.com/en/download/manual.jsp)) for JNIDAT 2.0 version.
Tested on Oracle Weblogic 11 and Java JRE 8 for JNIDAT 1.0 version.

**Notices**: 
* If you have problems to connect to older Weblogic server with jnidat v2.0, you should try the JNDIAT v1.0. Indeed, jndiat 2.0 use weblogic v12 libraries. jndiat 1.0 uses older weblogic libraries.
* Don't use OpenJDK for running Jnidat jar file.
