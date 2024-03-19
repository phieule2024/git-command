# A-Z Git in 2 minutes 🔥

Here we go👇

## Core Commands:

- `git init`: Initialize a new Git repository in the current directory.
  Example: `git init`

- `git clone`: Clone a repository from a URL into a new directory.
  Example: `git clone https://github.com/user/repo.git`
  Clone with access_token `git clone https://[user_name]:[access_token]@github.com/[user_name]/[project_name].git`
- `git add`: Add changes in the current directory to the staging area.
  Example: `git add .`

- `git commit`: Commit the staged changes with a message.
  Example: `git commit -m "Initial commit"`

- `git status`: Show the status of files in the repository.
  Example: `git status`

- `git diff`: Show the difference between the working directory and the staging area.
  Example: `git diff`

- `git checkout`: Switch branches or restore files from the repository.
  Example: `git checkout branch_name`

- `git reset`: Reset the working directory to match the last commit.
  Example: `git reset --hard HEAD`

- `git log`: Show commit logs.
  Example: `git log`

- `git show`: Show information about a specific commit.
  Example: `git show commit_hash`

- `git tag`: Create a new tag for the current commit.
  Example: `git tag tag_name`

- `git push`: Push commits to a remote repository.
  Example: `git push origin branch_name`

- `git pull`: Fetch from and integrate with another repository or a local branch.
  Example: `git pull origin branch_name`

## Branching Commands:

- `git branch`: List, create, or delete branches.
  Example: `git branch`

- `git checkout -b`: Create and switch to a new branch.
  Example: `git checkout -b new_branch`

- `git merge`: Merge changes from another branch into the current branch.
  Example: `git merge branch_name`

- `git rebase`: Reapply commits on top of another base tip.
  Example: `git rebase branch_name`

- `git branch --set-upstream-to`: Set up the current branch to track a remote branch.
  Example: `git branch --set-upstream-to=origin/remote_branch`

- `git branch --unset-upstream`: Unset the tracking information for the current branch.
  Example: `git branch --unset-upstream`

- `git cherry-pick`: Apply changes introduced by some existing commits.
  Example: `git cherry-pick commit_hash`

## Merging Commands:

- `git merge`: Merge changes from another branch into the current branch.
  Example: `git merge branch_name`

- `git rebase`: Reapply commits on top of another base tip.
  Example: `git rebase branch_name`

## Stashing Commands:

- `git stash`: Stash changes in the working directory.
  Example: `git stash`

- `git stash pop`: Apply the most recently stashed changes and remove them from the stash list.
  Example: `git stash pop`

- `git stash list`: List all stashed changes.
  Example: `git stash list`

- `git stash apply`: Apply the most recently stashed changes without removing them from the stash list.
  Example: `git stash apply`

- `git stash drop`: Remove the most recently stashed changes from the stash list.
  Example: `git stash drop`

## Remotes Commands:

- `git remote`: List remote repositories.
  Example: `git remote -v`

- `git remote add`: Add a new remote repository.
  Example: `git remote add origin <remote_repository_url>`

- `git remote remove`: Remove a remote repository.
  Example: `git remote remove origin`

- `git fetch`: Download objects and refs from another repository.
  Example: `git fetch origin`

- `git pull`: Fetch from and integrate with another repository or a local branch.
  Example: `git pull origin master`

- `git push`: Update remote refs along with associated objects.
  Example: `git push origin master`

- `git clone --mirror`: Clone a repository into a bare repository.
  Example: `git clone --mirror <remote_repository_url>`

## Configuration Commands:

- `git config`: Get and set repository or global options.
  Example: `git config user.name "John Doe"`

- `git global config`: Set global configuration options.
  Example: `git config --global user.email "john@example.com"`

- `git reset config`: Unset a specific configuration variable.
  Example: `git config --unset user.name`

## Plumbing Commands:

- These are lower-level Git commands typically used by Git itself or by other Git commands and scripts.
  Example: `git cat-file -p <object_id>`

## Porcelain Commands:

- These are higher-level Git commands designed for end-users and provide a more user-friendly interface.
  Example: `git blame <file>`

## Alias Commands:

- Define a shortcut for a Git command.
  Example: `git config --global alias.co checkout`

## Hook Commands:

- Set the path to the directory where Git hooks are stored.
  Example: `git config --local core.hooksPath <path>`

## Experimental Commands:

These commands are experimental and may not be fully supported or stable. Use them with caution.

- `git experimental-feature`: Description of the experimental feature.
- `git new-command`: Description of the new experimental command.
- `git dev-tool`: Description of the experimental development tool.

Remember to consult the official Git documentation or release notes for more information on experimental features and commands


### Some good resources to Learn Git faster ☺️

1. [Git Official Documentation](https://git-scm.com/doc)
2. [GitHub Learning Lab](https://udacity.com/course/version-control-with-git--ud123)
3. [Codecademy Course](https://codecademy.com/learn/learn-git)
4. [Pro Git by Scott Chacon (Book)](https://git-scm.com/book/en/v2)
5. YouTube
   - [FreeCodeCampOrg- beginner](https://rb.gy/ljxt5s)
   - [FreeCodeCampOrg- Intermediate](https://rb.gy/1x6mc)
   - Programming with Mosh

Feel free to add anything I missed 😊
