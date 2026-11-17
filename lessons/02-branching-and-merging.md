# Lesson 02: Branching and Merging

Branches let you develop features or fixes in isolation without affecting `main`.

## Key Commands
- `git checkout -b feature/name` (or `git switch -c feature/name`) — Create and switch to a new branch.
- `git branch` — List local branches.
- `git merge feature/name` — Combine another branch into your current branch.

## Fast-Forward vs 3-Way Merge
- **Fast-forward:** Moves the branch pointer forward when `main` has no new commits.
- **3-way merge:** Creates a merge commit when both branches have diverged.
