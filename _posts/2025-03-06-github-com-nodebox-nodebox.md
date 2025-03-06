---
title: nodebox
categories: ['java', 'nodebox', 'graphics']
---
## [nodebox](https://github.com/nodebox/nodebox)

### Node-based data application for visualization and generative design


NodeBox requires the [Java JDK](https://jdk.java.net/15/), and [Homebrew](https://brew.sh/) (for Ant and Maven)

NodeBox uses Ant and Maven to build a running version. Install these first:

```shell
brew install ant maven
```

Then from the Terminal, run:

```shell
git clone https://github.com/nodebox/nodebox.git
cd nodebox
ant run

# To create a full app (the build will be in dist/mac):
ant dist-mac
```
