---
title: resque-scheduler
categories: ['ruby']
---
## [resque-scheduler](https://github.com/resque/resque-scheduler)

### A light-weight job scheduling system built on top of Resque


Resque-scheduler is an extension to [Resque](http://github.com/resque/resque)
that adds support for queueing items in the future.

Job scheduling is supported in two different ways: Recurring (scheduled) and
Delayed.

Scheduled jobs are like cron jobs, recurring on a regular basis.  Delayed
jobs are resque jobs that you want to run at some point in the future.
The syntax is pretty explanatory:

```ruby
Resque.enqueue_in(5.days, SendFollowupEmail, argument) # runs a job in 5 days, calling SendFollowupEmail.perform(argument)
# or
Resque.enqueue_at(5.days.from_now, SomeJob, argument) # runs a job at a specific time, calling SomeJob.perform(argument)
```
