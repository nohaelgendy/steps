# Git Branch Commands

This guide provides common Git commands for creating, switching, renaming, deleting branches, and merging branches into the main branch in your Git repository.

### Create a New Branch
Creates a new branch named new-branch-name and switches to it.
```sh
git checkout -b new-branch-name
```

### List Branches
Lists all local branches in the repository.
```sh
git branch
```

### Switch to a Branch
Switches to an existing branch named branch-name.
```sh
git checkout branch-name
```

### Rename a Branch
Renames the current branch to new-branch-name.
```sh
git branch -m new-branch-name
```

### Delete a Branch
Deletes the specified branch named branch-name.
```sh
git branch -d new-branch-name
```

### Force Delete a Branch
Forces deletion of the specified branch, even if changes are not merged.
```sh
git branch -D branch-name
```

### Merge a Branch into Main
Merges changes from branch-name into the main branch.
```sh
git checkout main
git merge branch-name
```



