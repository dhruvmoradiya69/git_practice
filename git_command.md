# Unique Git Commands

## `git status`
Shows the working directory and staging area status. It tells you which files are staged, unstaged, or untracked.

## `git add <file>`
Stages the specified file, or files, for the next commit. For example, `git add nibbi.txt` stages the `nibbi.txt` file.

## `git rm --cached <file>`
Removes a file from the staging area, but keeps it in the working directory. This is useful for untracking files without deleting them.

## `git commit -m "<message>"`
Records the staged changes to the repository with a message describing the commit.

## `git log`
Shows the commit history for the current branch, displaying commits in reverse chronological order.

## `git log --oneline --graph --all`
Displays the commit history in a compact form (`--oneline`), with a visual representation of branches (`--graph`), and includes all branches (`--all`).

## `git branch`
Lists all local branches in the repository. The current branch will be marked with an asterisk.

## `git checkout -b <branch>`
Creates and switches to a new branch. For example, `git checkout -b dev` creates and checks out a new branch named `dev`.

## `git switch <branch>`
Switches to a specified branch. This is an alternative to `git checkout`.

## `git switch -c <branch>`
Creates and switches to a new branch in one step.

## `git checkout <branch>`
Switches to the specified branch. It is an older command that’s now somewhat replaced by `git switch` for simplicity.

## `git brnach` (Likely a typo)
This seems to be a typo of `git branch`, which lists the branches. Make sure to use the correct spelling.

## `git checkout master`
Switches to the `master` branch, which is often the default branch of a repository.

## `git checkout -b from-dev`
Creates and checks out a new branch from the `dev` branch, naming it `from-dev`.

## `git restore <file>`
Restores a file in the working directory to its last committed state, discarding changes.

## `git switch main`
Switches to the `main` branch. `main` is becoming the default branch name in many repositories, replacing `master`.

