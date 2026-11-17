# Lesson 11: GitHub Actions CI/CD

Workflows live under `.github/workflows/*.yml` and automate builds, tests, and deployments.

## Core Concepts
- **Events (`on`):** Triggers like `push` or `pull_request`.
- **Jobs:** Independent sets of steps running on a runner (e.g., `ubuntu-latest`).
- **Steps:** Individual shell commands or reusable actions (`actions/checkout`).
