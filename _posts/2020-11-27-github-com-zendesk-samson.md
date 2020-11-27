---
title: samson
categories: ['ruby', 'kubernetes', 'cd']
---
## [samson](https://github.com/zendesk/samson)

### Web interface for deployments, with plugin architecture and kubernetes support


Create a project and 1 or more stages (staging/production etc),
then selects a version and start the deploy.

Samson will:
 - clone git repository
 - execute commands associated with the stage (or execute API calls for kubernetes)
 - stream deploy output to everybody who wants to watch
 - persist deploy output for future review
