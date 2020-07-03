---
title: telegram-history-dump
categories: ['ruby']
---
## [telegram-history-dump](https://github.com/tvdstaaij/telegram-history-dump)

### Backup Telegram chat logs using telegram-cli


This utility is the successor of [telegram-json-backup][1], written from the
ground up in Ruby. It can create backups of your Telegram user and (super)group
dialogs using telegram-cli's remote control feature.
 
Compared to the old project, telegram-history-dump:

* Has better support for media downloads
* Supports output formats other than JSON and is extensible with custom formats
* Supports incremental backup (only new messages are downloaded)
* Does not depend on unstable Python/Lua bindings within telegram-cli
* Has a separate YAML formatted configuration file

The default configuration will backup all dialogs to a directory named `output`,
in JSON format, without downloading any media.
