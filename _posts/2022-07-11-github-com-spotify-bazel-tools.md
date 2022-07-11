---
title: bazel-tools
categories: ['java', 'bazel-rules', 'build-tool']
---
## [bazel-tools](https://github.com/spotify/bazel-tools)

### Tools for dealing with very large Bazel-managed repositories


This repository contains a collection of tools for working with Bazel workspaces; mostly tailored
towards writing JVM backend services.

  - [depfuzz](depfuzz) - A tool for removing unused dependencies with a fuzzing strategy.
  - [expand-macros](expand-macros) - A tool for expanding Bazel macros into the rules that they
    generate.
  - [format](format) - A tool for formatting all files in the repository according to common style
    guides.
  - [unused](unused) - A tool for showing source files that are not used in the build.
  - [sync-deps](sync-deps) - A tool for synchronizing third-party dependencies.
  - [sync-repos](sync-repos) - A tool for synchronizing third-party repositories.

These tools are being used in production at Spotify but have been built for very specific use-cases.
They will continue to evolve and cover more use-cases as they mature.
