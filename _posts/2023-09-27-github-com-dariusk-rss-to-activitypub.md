---
title: rss-to-activitypub
categories: ['javascript', 'activitypub', 'rss']
---
## [rss-to-activitypub](https://github.com/dariusk/rss-to-activitypub)

### An RSS to ActivityPub converter.


This is a server that lets users convert any RSS feed to an ActivityPub actor that can be followed by users on ActivityPub-compliant social networks like Mastodon.

This is based on my [Express ActivityPub Server](https://github.com/dariusk/express-activitypub), a simple Node/Express server that supports a subset of ActivityPub.

As of the `v2.0.0` release of this project, only users who are authenticated with a particular OAuth server can _create_ feeds. Any federated user can still read the feeds. I implemented this because running this service in the open invited thousands of spammers to create feeds and overwhelm the service. With this new model, you can run this as an added bonus for people in a community like a Mastodon server, and as the person running it you are taking on only the moderation burden of the users you are already responsible for on your federated server.
