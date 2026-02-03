# Repo Automation Template (Ethan-Personal)

This repository comes preconfigured with issue automation:
- dependency-based status labels (blocked/ready/in-progress)
- feature rollup to done when all child tasks/research are complete
- Project v2 Stage sync

## Required setup after creating a repo from this template

### 1) Add repo variable
Settings → Secrets and variables → Actions → Variables
- PROJECT_NUMBER = <your org project number>

### 2) Ensure secret is available
Settings → Secrets and variables → Actions → Secrets
- ORG_WORKFLOW_TOKEN must exist (recommended as an org secret)

### 3) (Optional) Run validation
Actions → Integration Test - Issue Automation → Run workflow