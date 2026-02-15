---
title: rails_event_store
categories: ['ruby', 'event-sourcing', 'rails']
---
## [rails_event_store](https://github.com/RailsEventStore/rails_event_store)

### A Ruby implementation of an Event Store based on Active Record


[Rails Event Store (RES)](https://railseventstore.org/) is a library for publishing, consuming, storing and retrieving events. It's your best companion for going with an event-driven architecture for your Rails application.

You can use it:

*   as your [Publish-Subscribe bus](https://railseventstore.org/docs/pubsub/)
*   to decouple core business logic from external concerns in Hexagonal style architectures
*   as [an alternative to ActiveRecord callbacks and Observers](https://blog.arkency.com/2016/05/domain-events-over-active-record-callbacks/)
*   as a communication layer between loosely coupled components
*   to react to published events synchronously or asynchronously
*   to extract side-effects (notifications, metrics etc) from your controllers and services into event handlers
*   to build an audit-log
*   to create read-models
*   to implement event-sourcing
