---
title: workflow-dispatch
categories: ['typescript', 'github-actions', 'github']
---
## [workflow-dispatch](https://github.com/benc-uk/workflow-dispatch)

### A GitHub Action for triggering workflows, using the `workflow_dispatch` event


This action triggers another GitHub Actions workflow, using the `workflow_dispatch` event.  
The workflow must be configured for this event type e.g. `on: [workflow_dispatch]`

This allows you to chain workflows, the classic use case is have a CI build workflow, trigger a CD release/deploy workflow when it completes. Allowing you to maintain separate workflows for CI and CD, and pass data between them as required.

For details of the `workflow_dispatch` even see [this blog post introducing this type of trigger](https://github.blog/changelog/2020-07-06-github-actions-manual-triggers-with-workflow_dispatch/)

*Note 1.* The GitHub UI will report flows triggered by this action as "manually triggered" even though they have been run programmatically via another workflow and the API

*Note 2.* If you want to reference the target workflow by ID, you will need to list them with the following REST API call `curl https://api.github.com/repos/{{owner}}/{{repo}}/actions/workflows -H "Authorization: token {{pat-token}}"`
