---
title: kafka-connect-twitter
categories: ['java', 'kafka-connect', 'twitter']
---
## [kafka-connect-twitter](https://github.com/jcustenborder/kafka-connect-twitter)

### Kafka Connect connector to stream data in real time from Twitter.


This connector uses the twitter streaming api to listen for status update messages and 
convert them to a Kafka Connect struct on the fly. The goal is to match as much of the 
Twitter Status object as possible.
