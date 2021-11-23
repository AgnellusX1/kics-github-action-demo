# 🤖 KICS GitHub Actions Demo

This repository shows how KICS GitHub Action can be set and was fully inspired by the documentation on [KICS GitHub Actions Marketplace tutorial](https://github.com/marketplace/actions/kics-github-action#simple-usage-example).
To check how the action was made, you just need to look on [.github/workflows/kics-scan=action.yml](https://github.com/Checkmarx/kics-github-action-demo/blob/main/.github/workflows/kics-scan-action.yml) file and see a simple example of how to use KICS features in your GitHub Actions Pipeline.

To check results examples, you can look at [Actions tab](https://github.com/Checkmarx/kics-github-action-demo/actions) and select a workflow that is finished. You will see multiples failures, this is intended to generate outputs so you can check how KICS create *Annotations* and upload reports as *Artifacts* to be downloaded.

Also, you can check the [Security tab](https://github.com/Checkmarx/kics-github-action-demo/security) on [Code scanning alerts](https://github.com/Checkmarx/kics-github-action-demo/security/code-scanning) section and see how KICS uses sarif reports to generate scanning issues.
