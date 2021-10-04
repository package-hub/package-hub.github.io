---
title: paperless-ng
categories: ['python', 'dms', 'document-management-system']
---
## [paperless-ng](https://github.com/jonaswinkler/paperless-ng)

### A supercharged version of paperless: scan, index and archive all your physical documents


[Paperless (click me)](https://github.com/the-paperless-project/paperless) is an application by Daniel Quinn and contributors that indexes your scanned documents and allows you to easily search for documents and store metadata alongside your documents.

Paperless-ng is a fork of the original project, adding a new interface and many other changes under the hood. These key points should help you decide whether Paperless-ng is something you would prefer over Paperless:

* Interface: The new front end is the main interface for Paperless-ng, the old interface still exists but most customizations (such as thumbnails for the document list) have been removed.0
* Encryption: Paperless-ng does not support GnuPG anymore, since storing your data on encrypted file systems (that you optionally mount on demand) achieves about the same result.
* Resource usage: Paperless-ng does use a bit more resources than Paperless. Running the web server requires about 300MB of RAM or more, depending on the configuration. While adding documents, it requires about 300MB additional RAM, depending on the document. It still runs on Raspberry Pi (many users do that), but it has been generally geared to better use the resources of more powerful systems.
* API changes: If you rely on the REST API of paperless, some of its functionality has been changed.

For a detailed list of changes, have a look at the [change log](https://paperless-ng.readthedocs.io/en/latest/changelog.html) in the documentation, especially the section about the [0.9.0 release](https://paperless-ng.readthedocs.io/en/latest/changelog.html#paperless-ng-0-9-0).
