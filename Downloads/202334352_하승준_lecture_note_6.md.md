# 202334352_하승준

# Git Commands Cheat Sheet

This cheat sheet is designed to help you remember essential Git commands.

## Initializing a Repository in an Existing Directory

- **Command:** `git init`
- **Description:** Initializes a Git repository in the current directory.

## Checking Repository Status

- **Command:** `git status`
- **Description:** Displays the current repository status, indicating staged and unstaged changes.

## Adding a New File to Be Staged (Tracked)

- **Command:** `git add [file_name]`
- **Description:** Stages a new file to be tracked in the repository.

## Unstaging a File

- **Command:** `git rm --cached [file_name]`
- **Description:** Removes a file from the staging area.

## Ignoring a File

- **Source:** Chacon and Straub, Pro Git (2nd edition)
- **Description:** Use a `.gitignore` file to specify files or patterns to be ignored.

## Committing Changes

- **Command:** `git commit -m "commit message"`
- **Description:** Commits changes with a descriptive commit message.

## Changing Branch Name

- **Command:** `git branch -m <new_branch_name>`
- **Description:** Renames the current branch to the specified new branch name.
