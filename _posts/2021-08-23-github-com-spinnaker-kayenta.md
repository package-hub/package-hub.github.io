---
title: kayenta
categories: ['java', 'hacktoberfest']
---
## [kayenta](https://github.com/spinnaker/kayenta)

### Automated Canary Service

A canary release is a technique to reduce the risk from deploying a new version of software into production. A new version of software, referred to as the canary, is deployed to a small subset of users alongside the stable running version. Traffic is split between these two versions such that a portion of incoming requests are diverted to the canary. This approach can quickly uncover any problems with the new version without impacting the majority of users.

The quality of the canary version is assessed by comparing key metrics that describe the behavior of the old and new versions. If there is significant degradation in these metrics, the canary is aborted and all of the traffic is routed to the stable version in an effort to minimize the impact of unexpected behavior.

Canaries are usually run against deployments containing changes to code, but they
can also be used for operational changes, including changes to configuration.
