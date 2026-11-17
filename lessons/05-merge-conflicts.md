# Lesson 05: Resolving Merge Conflicts

Conflicts happen when two branches edit the same lines differently.

## Conflict Markers
```text
<<<<<<< HEAD
Your current branch changes
=======
Incoming branch changes
>>>>>>> feature-branch
```

## Steps to Resolve
1. Open the conflicted file and choose or combine the desired changes.
2. Remove the `<<<<<<<`, `=======`, and `>>>>>>>` markers.
3. Run `git add <file>` and `git commit` to complete the merge.
