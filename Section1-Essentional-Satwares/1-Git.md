# Git Command Overview

## Basic Setup
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Core Commands
```bash
git init                    # Initialize a new repository
git clone <url>             # Clone an existing repository
git add <file>              # Stage changes
git commit -m "message"     # Commit staged changes
git push                    # Push commits to remote
git pull                    # Fetch and merge remote changes
git status                  # Show working directory status
git log                     # View commit history
```

## Branching
```bash
git branch                  # List branches
git branch <name>           # Create new branch
git checkout <branch>       # Switch branches
git checkout -b <branch>    # Create and switch to branch
git merge <branch>          # Merge branch into current branch
```

## Undoing Changes
```bash
git restore <file>          # Discard changes in working directory
git restore --staged <file> # Unstage file
git revert <commit>         # Create new commit that undoes changes
git reset <commit>          # Move HEAD to previous commit
```

## Stashing
```bash
git stash                   # Temporarily save changes
git stash pop               # Apply and remove stashed changes
```