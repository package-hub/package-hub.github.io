---
title: acmephp
categories: ['php']
---
## [acmephp](https://github.com/acmephp/acmephp)

### Let's Encrypt/ACME Command Line client written in PHP


Acme PHP provides several major improvements over the default clients:
-   Acme PHP comes by nature as a single binary file: a single download and you are ready to start working ;
-   Acme PHP is based on a configuration file (`~/.acmephp/acmephp.conf`) instead command line arguments.
    Thus, the configuration is much more expressive and the same setup is used at every renewal ;
-   Acme PHP can monitor your CRONs and can send you alerts in many differents places:
    E-mail, Slack, HipChat, Flowdock, Fleep (thanks to [Monolog](https://github.com/Seldaek/monolog)!)
-   Acme PHP is very extensible it to create the certificate files structure you need for your webserver.
    It brings several default formatters to create classical file structures
    (nginx, nginx-proxy, haproxy, etc.) but you can very easily create your own if you need to ;
-   Acme PHP follows a strict BC policy preventing errors in your scripts or CRON even if you update it (see
    [the Backward Compatibility policy of Acme PHP](#backward-compatibility-policy) for more informations) ;
