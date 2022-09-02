# Github Workflow Failure Issue Creation

This repo contains a workflow that is triggered by `workflow_dispatch` from other failed workflows. This workflow will create a [GitHub issue in this repo](https://github.com/hwwilliams/github-workflow-failure-issue-creation/issues) with context about the failed workflow that sent the dispatch.

The dispatch request is sent from a separate repo at https://github.com/hwwilliams/github-workflow-failure-dispatch
