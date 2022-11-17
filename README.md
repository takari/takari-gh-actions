# Takari Shared GitHub Actions


# Usage

Create GitHub workflow in project file:

```
.github/workflows/ci.yml
```

 with content:

```yaml

name: Verify

on:
  push:
  pull_request:

jobs:
  build:
    name: Verify
    uses: takari/takari-gh-actions/.github/workflows/ci.yml@v1

```

# Resources

- [Workflow syntax](https://docs.github.com/en/actions/learn-github-actions/workflow-syntax-for-github-actions)
- [Reusing workflows](https://docs.github.com/en/actions/learn-github-actions/reusing-workflows)

