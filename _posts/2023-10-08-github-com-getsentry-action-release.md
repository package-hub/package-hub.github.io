---
title: action-release
categories: ['typescript', 'tag-production']
---
## [action-release](https://github.com/getsentry/action-release)

### GitHub Action for creating a release on Sentry


**NOTE**: Currently only available for Linux runners. See [this issue](https://github.com/getsentry/action-release/issues/58) for more details.

Automatically create a Sentry release in a workflow.

A release is a version of your code that can be deployed to an environment. When you give Sentry information about your releases, you unlock a number of new features:

- Determine the issues and regressions introduced in a new release
- Predict which commit caused an issue and who is likely responsible
- Resolve issues by including the issue number in your commit message
- Receive email notifications when your code gets deployed

Additionally, releases are used for applying source maps to minified JavaScript to view original, untransformed source code. You can learn more about releases in the [releases documentation](https://docs.sentry.io/workflow/releases).
