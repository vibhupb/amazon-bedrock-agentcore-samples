# Disabled Workflows

GitHub Actions have been intentionally disabled for this repository.

## Why are workflows disabled?

This repository has been configured to not run GitHub Actions, even after fork syncs.

## Workflow files

All workflow files have been moved to this directory (`workflows-disabled`) to preserve them while keeping them inactive. GitHub Actions only runs workflows from the `.github/workflows/` directory.

## Re-enabling workflows

If you need to re-enable GitHub Actions in the future:
1. Move the desired workflow files from `.github/workflows-disabled/` back to `.github/workflows/`
2. Remove or update the README.md file in `.github/workflows/`

## Available workflow files:
- `ash-full-repository-scan.yml` - AWS Security Hub full repository scan
- `ash-security-comment.yml` - AWS Security Hub security comments
- `ash-security-scan.yml` - AWS Security Hub security scan
- `codeql.yml` - CodeQL security analysis
- `dependabot.yml` - Dependabot configuration
- `js-lint.yml` - JavaScript linting
- `label.yml` - PR labeling automation
- `python-lint.yml` - Python code quality checks
