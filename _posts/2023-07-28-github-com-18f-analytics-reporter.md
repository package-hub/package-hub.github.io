---
title: analytics-reporter
categories: ['javascript', 'analytics', 'google-analytics']
---
## [analytics-reporter](https://github.com/18F/analytics-reporter)

### Lightweight analytics reporting and publishing tool for Google Analytics data.


A lightweight system for publishing analytics data from Google Analytics profiles. Uses the [Google Analytics Core Reporting API v3](https://developers.google.com/analytics/devguides/reporting/core/v3/) and the [Google Analytics Real Time API v3](https://developers.google.com/analytics/devguides/reporting/realtime/v3/).

This is used in combination with [18F/analytics.usa.gov](https://github.com/18F/analytics.usa.gov) to power the government analytics hub, [analytics.usa.gov](https://analytics.usa.gov).

Available reports are named and described in [`reports.json`](reports/reports.json). For now, they're hardcoded into the repository.

