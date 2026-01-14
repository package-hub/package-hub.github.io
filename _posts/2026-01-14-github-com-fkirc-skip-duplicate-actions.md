---
title: skip-duplicate-actions
categories: ['typescript']
---
## [skip-duplicate-actions](https://github.com/fkirc/skip-duplicate-actions)

### Save time and cost when using GitHub Actions


`skip-duplicate-actions` provides the following features to optimize GitHub Actions:

- [Skip duplicate workflow runs](#skip-duplicate-workflow-runs) after merges, pull requests or similar.
- [Skip concurrent or parallel workflow runs](#skip-concurrent-workflow-runs) for things that you do not want to run twice.
- [Skip ignored paths](#skip-ignored-paths) to speedup documentation-changes or similar.
- [Skip if paths not changed](#skip-if-paths-not-changed) for something like directory-specific tests.
- [Cancel outdated workflow runs](#cancel-outdated-workflow-runs) after branch-pushes.

All of those features help to save time and costs; especially for long-running workflows.
You can choose any subset of those features.
