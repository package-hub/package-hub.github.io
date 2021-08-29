---
title: padloc
categories: ['typescript']
---
## [padloc](https://github.com/padloc/padloc)

### A modern, open source password manager for individuals and teams.


Simple, secure password and data management for individuals and teams (formerly known as Padlock).

This repo is split into multiple packages:

| Package Name                                   | Description                                                                                                                               |
| ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| [@padloc/core](packages/core)                  | Core Logic                                                                                                                                |
| [@padloc/app](packages/app)                    | Web-based UI components                                                                                                                   |
| [@padloc/server](packages/server)              | The Backend Server                                                                                                                        |
| [@padloc/pwa](packages/pwa)                    | The Web Client, a [Progressive Web App](https://developers.google.com/web/progressive-web-apps) built on top of the `@padloc/app` package |
| [@padloc/locale](packages/locale)              | Package containing translations and other localization-related things                                                                     |
| [@padloc/electron](packages/electron)          | The Desktop App, built with Electron                                                                                                      |
| [@padloc/cordova](packages/cordova)            | Cordova project for building iOS and Android app.                                                                                         |
| [@padloc/tauri (experimental)](packages/tauri) | Cross-platform native app builder for Padloc, powered by [Tauri](https://github.com/tauri-apps/tauri)                                     |
