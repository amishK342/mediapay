# Repo Context

This file helps Verity/Codex understand how to work in this repository.

## What Verity detected
- Detected at: 2026-04-01 09:36:25 UTC
- Repo: amishK342/mediapay
- Default branch: main

## Suggested commands (review before enabling automation)
These are written into `.verity/config.yml` (in a PR) if empty.

### Setup
- `cd frontend && npm ci`

### Tests
- `cd frontend && npm test`

### Build
- `cd frontend && npm run build`

### Deploy
_(none detected)_

## Notes for humans
- If you change commands here, also update `.verity/config.yml`.
- No secrets should be committed. Use GitHub Secrets.

## Auto Documentation Snapshot
<!-- verity:auto-doc:start -->
- Commit: `5e2404eb41b1beba29b32fb7e14e2cf3fee7a74e`
- Commit date: `2026-04-01T15:06:13+05:30`
- Repository: `amishK342/mediapay`
- Default branch: `main`

### Configured Commands
Setup:
- `cd frontend && npm ci`
Tests:
- `cd frontend && npm test`
Build:
- `cd frontend && npm run build`
Deploy:
_(none configured)_

### Top-level Directories
- `backend`
- `docs`
- `frontend`
- `scripts`

### Workflow Files
- `codex-deploy.yml`
- `codex-dev-cycle.yml`
- `codex-pr-review.yml`
- `codex-test-generation.yml`
- `codex-test-to-issue.yml`
- `codex-usecase-generation.yml`
- `verity-auto-docs.yml`
- `verity-command-router.yml`
- `verity-guardrails.yml`
- `verity-monitor.yml`
- `verity-repo-context-builder.yml`

### Enabled Policy Flags
- `- `openai_guardrail.enabled`: `True``
- `- `pr_review.enabled`: `True``
<!-- verity:auto-doc:end -->
