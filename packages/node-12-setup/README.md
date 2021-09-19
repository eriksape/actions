# `node-base` - **Github Action**

This action checks out the commit, sets up Node and installs deps using yarn.


## Example Workflow File

```yaml
name: Checkout and install deps

on: [pull_request]

jobs:
    checkout-and-yarn:
        runs-on: ubuntu-latest
        steps:
            - name: Checkout and yarn
              uses: eriksape/actions/packages/node-12-setup@main
```
