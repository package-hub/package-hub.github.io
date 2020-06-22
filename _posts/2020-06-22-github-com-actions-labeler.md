---
title: labeler
categories: ['typescript']
---
## [labeler](https://github.com/actions/labeler)

### An action for automatically labelling pull requests


Pull request labeler triages PRs based on the paths that are modified in the PR.

Note that only pull requests being opened from the same repository can be labeled.  This action will not currently work for pull requests from forks -- like is common in open source projects -- because the token for forked pull request workflows does not have write permissions.
