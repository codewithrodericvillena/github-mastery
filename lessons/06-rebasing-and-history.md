# Lesson 06: Rebasing and Clean History

## Key Commands
- `git rebase main` — Replay your branch commits on top of the latest `main`.
- `git rebase -i HEAD~3` — Interactively reorder, edit, or squash the last 3 commits.

## Golden Rule of Rebasing
Never rebase commits that have already been pushed to a shared branch used by others.
