# Lesson 07: Undoing Changes Safely

## Key Commands
- `git restore <file>` — Discard unstaged working-directory changes.
- `git restore --staged <file>` — Unstage a file without losing edits.
- `git revert <commit>` — Create a new commit that safely undoes a past commit (safe for shared branches).
- `git reset --soft HEAD~1` — Undo the last commit while keeping changes staged.
- `git reflog` — Recover lost commits or branch positions locally.
