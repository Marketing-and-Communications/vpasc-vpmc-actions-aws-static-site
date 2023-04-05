# vpasc-vpmc-actions-aws-static-site

GitHub Composite Action for deploying an AWS static website via CI/CD pipeline

## Usage
This repository uses semantic versioning to enable major, minor, and patch
version pinning. 

Use this action within another GitHub Action as follows *(note: the version pin
should change appropriately)*:

```yaml
steps:
  - name: Create an AWS static website plan or apply one
    uses: Marketing-and-Communications/vpasc-vpmc-actions-aws-static-site@v1.0
```


## Deploying a new release
Create a new release with proper version tag (i.e., v1.0.0) and a workflow will
automatically update the tags to enable proper semantic versioning.