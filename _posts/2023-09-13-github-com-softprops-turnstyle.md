---
title: turnstyle
categories: ['typescript', 'github-actions']
---
## [turnstyle](https://github.com/softprops/turnstyle)

### 🎟️A GitHub Action for serializing workflow runs


GitHub Actions is an event-oriented system. Your workflows run in response to events and are triggered independently and without coordination. In a shared repository, if two or more people merge pull requests, each will trigger workflows without regard to one another.

This can be problematic for workflows used as part of a continuous deployment process. You might want to let an in-flight deployment complete before progressing further with the next workflow. This is the usecase turnstyle action targets.
