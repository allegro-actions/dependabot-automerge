# Dependabot Auto Merge
This GitHub Action automatically approves and merges pull requests created by Dependabot.

## Usage

Add permissions

```yaml
permissions:
  contents: write
  pull-requests: write
  id-token: write
```

Use the action

```yaml
    steps:
      - uses: allegro-actions/dependabot-automerge@v1
```

Happy hacking!
