---
title: paths-filter
categories: ['typescript', 'github-actions', 'change-detection']
---
## [paths-filter](https://github.com/dorny/paths-filter)

### Conditionally run actions based on files modified by PR, feature branch or pushed commits


[GitHub Action](https://github.com/features/actions) that enables conditional execution of workflow steps and jobs, based on the files modified by pull request, on a feature
branch, or by the recently pushed commits.

Run slow tasks like integration tests or deployments only for changed components. It saves time and resources, especially in monorepo setups.
GitHub workflows built-in [path filters](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions#onpushpull_requestpaths)
don't allow this because they don't work on a level of individual jobs or steps.

**Real world usage examples:**

- [sentry.io](https://sentry.io/) - [backend-test-py3.6.yml](https://github.com/getsentry/sentry/blob/ca0e43dc5602a9ab2e06d3f6397cc48fb5a78541/.github/workflows/backend-test-py3.6.yml#L32)
- [GoogleChrome/web.dev](https://web.dev/) - [lint-and-test-workflow.yml](https://github.com/GoogleChrome/web.dev/blob/e1f0c28964e99ce6a996c1e3fd3ee1985a7a04f6/.github/workflows/lint-and-test-workflow.yml#L33)
