# Schedule a Python script with GitHub Actions


- Inspect and configure cron job in GitHub Action `.github/workflows/actions`
- Install and use third party packages from `requirements.txt`
- Secret environment variables can be used. Set secrets in Settings/Secrets/Actions -> 'New repository secret'. Use the same secret name inside your .yml and .py files
- Dont forget to allow Workflow (GitHub Actions) to write to the repo for the push back to branch at Settings/Actions/General->Workflow permissions
