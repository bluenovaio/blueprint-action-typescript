**IMPORTANT**: You need to follow the steps below to get started:

- [ ] Update the `action.yaml` with the correct data (i.e. Name of project, inputs, outputs etc.)
- [ ] Update the `package.json` with the correct name, version, etc.
- [ ] Update the `README.md` with the correct information & documentation.
- [ ] Add Unit Tests and remove `--passWithNoTests` argument in then `"scripts"` section of the `package.json`.

# blueprint-action-typescript
Template repository for TypeScript Github Actions.

## Usage
> Update the following to give a quick C&P example that developers can use.

```yaml
name: Example Action 
on:
  push

jobs:
  testJob:
    name: Test
    runs-on: ubuntu-latest
    steps:
      - run: <YOUR-ACTION> 
```

#### Attribution

The OSS policies in this repository are based on [this](https://github.com/auth0/open-source-template) repo by Auth0.
