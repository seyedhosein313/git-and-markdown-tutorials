# Git Commands

## General Configuration
- `git -v` (or `git --version`): Display the installed Git version.
- `git config --global user.name "your-username"`: Set the global username for Git commits.
- `git config --global user.email "your-email@example.com"`: Set the global email for Git commits.

## Initializing and Adding Changes
- `git init`: Initialize a new Git repository in the current directory.
- `git add`: Stage specific files for the next commit.
- `git add .`: Stage all changes (new, modified, and deleted files) for the next commit.

## Committing Changes
- `git commit -m "Message"`: Commit staged changes with a descriptive message.

## Viewing History
- `git log`: View the commit history with detailed information.
- `git log --oneline`: View the commit history in a concise format.

## Branching and Switching
- `git branch`: List all branches in the repository.
- `git branch name-branch`: Create a new branch with the specified name.
- `git switch name-branch`: Switch to an existing branch.
- `git checkout master`: Switch to the master branch.
- `git checkout 1a2b3c4`: Check out a specific commit by its hash.

## Merging and Syncing
- `git merge name-branch`: Merge the specified branch into the current branch.

## Remote Repositories
- `git remote add origin https://github.com/username/name-repo.git`: Add a remote repository with the name "origin".
- `git remote`: List all remote repositories.
- `git clone https://github.com/username/name-repo.git`: Clone an existing repository to your local machine.

## Pushing and Pulling
- `git push -u origin master`: Push the master branch to the remote repository and set upstream tracking.
- `git push`: Push committed changes to the current branch's remote tracking branch.
- `git pull origin master`: Fetch and merge changes from the master branch of the remote repository.
- `git push --set-upstream origin name-branch`: Push a branch to the remote repository and set upstream tracking.