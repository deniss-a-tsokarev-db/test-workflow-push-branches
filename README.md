# test-workflow-push-branches
Testing workflow triggers on push to "!main"

### [test_wf_a.yaml](./.github/workflows/test_wf_a.yaml)
```yaml
on:
  push:
    branches: 
      - "!main"
```

### [test_wf_b.yaml](./.github/workflows/test_wf_b.yaml)
```yaml
on:
  push:
    branches: 
      - "**"
      - "!main"
```
