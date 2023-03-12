---
title: owasp-threat-dragon
categories: ['javascript']
---
## [owasp-threat-dragon](https://github.com/mike-goodwin/owasp-threat-dragon)

### An open source, online threat modelling tool from OWASP


Threat Dragon is a free, open-source, cross-platform threat modelling application including system diagramming and a threat rule engine to auto-generate threats/mitigations. It is an [OWASP Incubator Project](https://www.owasp.org/index.php/OWASP_Threat_Dragon). The focus of the project is on great UX, a powerful rule engine and integration with other development lifecycle tools.

The application comes in two variants:

1. [**A web application (this repo)**](https://github.com/mike-goodwin/owasp-threat-dragon): For the web application, models files are stored in GitHub (other storage will become available). We are currently maintaining [a working protoype](https://threatdragon.org) in synch with the master code branch.

2. [**A desktop application**](https://github.com/mike-goodwin/owasp-threat-dragon-desktop): This is based on [Electron](https://electron.atom.io/). There are installers available for both Windows and Mac OSX, as well as rpm and debian packages for Linux. Note that for the desktop variant the models are stored on the local filesystem rather than a remote repository.

[End user help](http://docs.threatdragon.org/) is available for both variants.

This repository contains the files for the web application variant.

Core files that are shared between both the desktop and web variants are stored in an [seperate repo](https://github.com/mike-goodwin/owasp-threat-dragon-core) and are installable as a [seperate package](https://www.npmjs.com/package/owasp-threat-dragon-core).
