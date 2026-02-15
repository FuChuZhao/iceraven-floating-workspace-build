# Iceraven Floating Workspace Build Repo

Public workflow-only repository.

- Trigger mode: `workflow_dispatch` only
- Pulls private source using deploy key secret: `SOURCE_REPO_SSH_KEY`
- Builds via source-controlled `tools/ci/build.sh`
- Uploads minimal artifacts with short retention
