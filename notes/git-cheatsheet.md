# Git Cheat Sheet

## Setup
    git config --global user.name "Your Name"
    git config --global user.email "you@example.com"
    git config --list

## Everyday workflow
    git status                 # see what changed
    git add <file>             # stage one file
    git add .                  # stage everything
    git commit -m "message"    # save a snapshot
    git push                   # send to GitHub
    git pull                   # get latest from GitHub

## Branches
    git branch                 # list branches
    git checkout -b new-branch # create and switch
    git checkout main          # switch back
    git merge new-branch       # merge into current branch

## Inspect
    git log --oneline          # short history
    git diff                   # unstaged changes

## Undo (carefully)
    git restore <file>         # discard changes in a file
    git restore --staged <file># unstage a file

## Golden rule
Never commit passwords, API keys, or private keys.
