---
title: gitreflow
categories: ['ruby', 'git', 'git-workflow']
---
## [gitreflow](https://github.com/reenhanced/gitreflow)

### Reflow automatically creates pull requests, ensures the code review is approved, and squash merges finished branches to master with a great commit message template.

Create and switch to new branch `nh-branchy-branch`:
```
    $ git reflow start nh-branchy-branch
```
Create a pull request for your branch against `master` or a custom `base-branch`:
```
    $ git reflow review
```
If your code is approved, merge to `base-branch` and delete the feature branch:
```
    $ git reflow deliver
```

----
