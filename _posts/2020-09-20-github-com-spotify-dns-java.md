---
title: dns-java
categories: ['java', 'dnsjava', 'dns']
---
## [dns-java](https://github.com/spotify/dns-java)

### DNS wrapper library that provides SRV lookup functionality


Sometimes it is useful to default to previously returned, retained values, if a dns lookup should 
fail or return an empty result. This behavior is controlled by the ```retainingDataOnFailures()``` 
and  ```retentionDurationMillis(long)``` methods in
[DnsSrvResolvers.DnsSrvResolverBuilder](src/main/java/com/spotify/dns/DnsSrvResolvers.java).
