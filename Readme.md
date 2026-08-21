## TaaS GitHub Action

This repo contains `.github/workflows/taas.yml`, which creates a GitHub check run and submits a TaaS job with callback information.

Configure these repository secrets before running the workflow:

```text
QCOM_API_KEY
GH_APP_CLIENT_ID
GH_APP_INSTALLATION_ID
GH_APP_PRIVATE_KEY
```

The GitHub App must be installed on this repo and must have:

```text
Repository permissions -> Checks: Read and write
```

Run it from the Actions tab with `workflow_dispatch`, or trigger it by pushing to `main` / opening a pull request.


