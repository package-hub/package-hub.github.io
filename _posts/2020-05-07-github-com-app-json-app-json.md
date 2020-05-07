---
title: app.json
categories: ['javascript']
---
## [app.json](https://github.com/app-json/app.json)

### A node module for working with app.json files and deploying app.json apps to Heroku. Designed to work on the server, the browser, and the command line.


`app.json` is a manifest format for describing web apps. It's a file in the root
directory of your app that describes build requirements, environment variables, addons,
and other information.

This repository contains the source for an npm module called
[app.json](https://www.npmjs.org/package/app.json), which has many facets:

- A JavaScript interface for creating, validating, and producing app.json manifests.
- A module that is designed to work in browsers and Node.js.
- A command-line interface (CLI) for cloning apps, creating manifests, and producing schema documentation.

For more info about `app.json`, see

- [Introducing the app.json Application Manifest](https://blog.heroku.com/archives/2014/5/22/introducing_the_app_json_application_manifest)
- [app.json Schema](https://devcenter.heroku.com/articles/app-json-schema)
- [Setting Up Apps using the Platform API](https://devcenter.heroku.com/articles/setting-up-apps-using-the-heroku-platform-api)