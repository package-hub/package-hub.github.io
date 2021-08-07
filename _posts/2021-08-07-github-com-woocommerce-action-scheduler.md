---
title: action-scheduler
categories: ['php', 'action-scheduler', 'wordpress']
---
## [action-scheduler](https://github.com/woocommerce/action-scheduler)

### A scalable, traceable job queue for background processing large queues of tasks in WordPress. Specifically designed for distribution in WordPress plugins (and themes) - no server access required.


Action Scheduler is a scalable, traceable job queue for background processing large sets of actions in WordPress. It's specially designed to be distributed in WordPress plugins.

Action Scheduler works by triggering an action hook to run at some time in the future. Each hook can be scheduled with unique data, to allow callbacks to perform operations on that data. The hook can also be scheduled to run on one or more occassions.

Think of it like an extension to `do_action()` which adds the ability to delay and repeat a hook.
