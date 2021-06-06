---
title: python-rtmbot
categories: ['python']
---
## [python-rtmbot](https://github.com/slackapi/python-rtmbot)

### A framework for receiving and interacting with events from Slack's RTM API


All events from the RTM websocket are sent to the registered plugins. To act on an event, create a function definition, inside your Plugin class, called process_(api_method) that accepts a single arg for data. For example, to handle incoming messages:

```python
    def process_message(self, data):
        print data
```

This will print the incoming message json (dict) to the screen where the bot is running.

Plugins having a method defined as `catch_all(self, data)` will receive ALL events from the websocket. This is useful for learning the names of events and debugging.

For a list of all possible API Methods, look here: https://api.slack.com/rtm

Note: If you're using Python 2.x, the incoming data should be a unicode string, be careful you don't coerce it into a normal str object as it will cause errors on output. You can add `from __future__ import unicode_literals` to your plugin file to avoid this.
