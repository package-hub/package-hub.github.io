---
title: zhong
categories: ['ruby', 'cron', 'redis']
---
## [zhong](https://github.com/nickelser/zhong)

### Reliable, distributed cron.


Useful, reliable distributed cron. Tired of your cron-like scheduler running key jobs twice? Would you like to be able to run your cron server on multiple machines and have it "just work"? Have we got the gem for you.

Zhong uses Redis to acquire exclusive locks on jobs, as well as recording when they last ran. This means that you can rest easy at night, knowing that your customers are getting their monthly Goat Fancy magazine subscriptions and you are rolling around in your piles of money without a care in the world.

:tangerine: Battle-tested at [Instacart](https://www.instacart.com/opensource)