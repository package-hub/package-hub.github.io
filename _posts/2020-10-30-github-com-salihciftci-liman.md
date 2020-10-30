---
title: liman
categories: ['javascript', 'docker', 'container']
---
## [liman](https://github.com/salihciftci/liman)

### Self-hosted web application for monitoring docker.


Best way to use Liman is using Docker image.

```
$ docker volume create liman
$ docker run -it -v /var/run/docker.sock:/var/run/docker.sock -v liman:/liman/data salihciftci/liman
```

Note: the `-v /var/run/docker.sock:/var/run/docker.sock` option can be used in Linux environments only. 
