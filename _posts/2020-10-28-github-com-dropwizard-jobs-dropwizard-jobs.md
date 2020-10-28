---
title: dropwizard-jobs
categories: ['java', 'quartz-scheduler', 'dropwizard']
---
## [dropwizard-jobs](https://github.com/dropwizard-jobs/dropwizard-jobs)

### Scheduling / Quartz integration for Dropwizard


This plugin integrates the [quartz scheduler](http://quartz-scheduler.org/) with dropwizard and allows you to easily create background jobs, which are not bound to the HTTP request-response cycle.
Quartz creates a threadpool on application startup and uses it for background jobs.

There are four different types of jobs:

* Jobs run on application start for initial setup (could also be done via a managed instance in dropwizard)
* Jobs run at application stop before the application is closed (could also be done via managed instance in dropwizard)
* Jobs which are repeated after a certain time interval
* Jobs which need to run at a specific time, via a cron-like expression
