---
title: transitland-datastore
categories: ['ruby', 'transit', 'gtfs']
---
## [transitland-datastore](https://github.com/transitland/transitland-datastore)

### Transitland's centralized web service API for both querying and editing aggregated transit data from around the world


A community-run and -edited timetable and map of public transit service around the world.

***For more information about Transitland as a whole, and how to use the Datastore in particular, view the [Transitland documentation site](https://transit.land/documentation).***

This readme describes the Transitland Datastore behind the scenes: a Ruby on Rails web service (backed by Postgres/PostGIS), along with an asynchronous Sidekiq queue (backed by Resque) that runs Ruby and Python data-ingestion libraries.

Note that this web application is designed to run at `https://transit.land/api/v1` While you're welcome to try hosting your own instance, please keep in mind that the Transitland Datastore is intended to be a centralized source of data run by a community in one place (much like [the Rails app that powers the openstreetmap.org API](https://github.com/openstreetmap/openstreetmap-website)).
