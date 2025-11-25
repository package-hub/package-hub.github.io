---
title: meta
categories: ['javascript', 'git', 'repository']
---
## [meta](https://github.com/mateodelnorte/meta)

### tool for turning many repos into a meta repo. why choose many repos or a monolithic repo, when you can have both with a meta repo?


meta is a tool for managing multi-project systems and libraries. It answers the conundrum of choosing between a mono repo or many repos by saying "both", with a meta repo!

meta is powered by plugins that wrap common commands, letting you execute them against some or all of the repos in your solution at once. meta is built on [loop](https://github.com/mateodelnorte/loop), and as such inherits loops ability to easily target a particular set of directories for executing a common command (eg `meta git status --include-only dir1,dir2`. See [loop](https://github.com/mateodelnorte/loop) for more available options).

meta is packaged with a few of these core plugins by default: https://github.com/mateodelnorte/meta/blob/master/package.json#L63-L66
