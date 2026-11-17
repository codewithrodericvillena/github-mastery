# Lesson 12: Branch Protection and Rulesets

Protecting `main` prevents accidental force-pushes and broken builds.

## Common Rules
- Require pull requests before merging.
- Require at least 1 approving review.
- Require status checks (CI tests) to pass before merging.
- Block force pushes and branch deletion.
