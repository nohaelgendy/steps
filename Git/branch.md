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

### Add Changes to a Branch
```sh
# Check the current branch (optional)
git branch

# Switch to the desired branch
git checkout branch_name

# Stage your changes
git add .

# Commit your changes
git commit -m "Your commit message"

# Push the changes to the remote repository
git push origin branch_name
```
Replace branch_name with the name of your branch and "Your commit message" with a descriptive message about what changes you have made.

### Merge a Branch into Main
Merges changes from branch-name into the main branch.
```sh
# Switch to the main branch
git checkout main

# Pull the latest changes on the main branch
git pull origin main

# Merge the changes from your branch into the main branch
git merge branch_name

# Push the updated main branch to the remote repository
git push origin main
```
Replace branch_name with the name of your branch and "Commit message for your changes" with a descriptive message about what changes you have made.


