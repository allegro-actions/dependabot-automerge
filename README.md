# Dependabot Auto Merge

## Description
This GitHub Action automatically approves and merges pull requests created by Dependabot.

## Usage
Create a workflow in your repository using this action. 

Below is an example configuration:

```yaml
name: Dependabot auto merge
on:
  pull_request:
    types: [opened]
jobs:
  auto-merge:
    runs-on: [self-hosted, ubuntu-latest]
    steps:
      - uses: allegro-actions/dependabot-automerge@v1
```
