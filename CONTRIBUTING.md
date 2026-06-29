# Contributing to python-sdk

Thanks for your interest in contributing! This repo is community-supported — we welcome PRs but response times may vary.

## Getting started

1. Fork the repo and clone your fork
2. Create a virtual environment: `python -m venv venv && source venv/bin/activate`
3. Install dependencies: `pip install -r requirements.txt`
4. Create a feature branch: `git checkout -b my-fix`

## Making changes

- Keep PRs focused on a single change
- Add/update usage examples in the README if you change public behavior
- Never commit API keys or tokens — use environment variables (see README for the expected variable names)

## Linting

We run `ruff` for linting on all PRs. Before submitting, run:

```
pip install ruff
ruff check .
```

## Submitting a PR

1. Push your branch and open a PR against `main`
2. Fill in the PR template describing what changed and why
3. Ensure the CI lint check passes
4. A maintainer will review and merge

## Reporting issues

Open a GitHub issue with:
- What you expected to happen
- What actually happened
- Steps to reproduce (including Jaws API endpoint/version if relevant)
