# Git Commands Overview

## git config
A command to set configuration values for your Git installation. With this command for example you can set the user information. GitHub will use this across all your repositories.

## git init
It initializes a new Git repository in the current directory. Creates a hidden .git folder that contains all necessary metadata for version tracking.

## git commit
The command creates a new snapshot of the changes with a message describing the changes. This command permanently stores the staged changes in the Git repository.

## git status
Shows the current state of your working directory and staging area. It displays which files are tracked (or untracked), modified and which changes are for commit.

## git add
Adds files or applies changes to the index. This command marks specific files to be included in the next version snapshot.

## git log
Displays a chronological list of commits: commit IDs, authors, dates and commit messages. Helps to track the history of changes in the repository.

## git diff
Shows the differences between the working directory and the staging area or between commits. Its useful for reviewing changes before committing them.

## git pull
Fetches changes from a remote repository and integrates them into the current branch. Combines 'git fetch' and 'git merge' into one command.

## git push
Uploads local repository content to a remote repository. It's used to share your changes with others or to backup the work to a remote server.

## git branch
Lists, creates or deletes branches. Branches allow to develop features, fix bugs or experiment with new ideas in a isolated place from the main codebase.

## git checkout
Switches between branches or restores working tree files. It can also be used to create a new branch with the -b option.

## git merge
Combines changes from different branches. It incorporates the changes from the specified branch into the current branch --> creating a new merge commit.