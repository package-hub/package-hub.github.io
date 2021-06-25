---
title: previewgenerator
categories: ['php']
---
## [previewgenerator](https://github.com/nextcloud/previewgenerator)

### Nextcloud app to do preview generation


Nextcloud app that allows admins to pre-generate previews. The app listens to 
edit events and stores this information. Once a cron job is triggered it will
start preview generation. This means that you can better utilize your
system by pre-generating previews when your system is normally idle and thus 
putting less load on your machine when the requests are actually served.

The app does not replace on demand preview generation so if a preview is 
requested before it is pre-generated it will still be shown.
