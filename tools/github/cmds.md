# Github Commands

> List of common useful Github Commands to use 

`git init` : Initialize git in the current working directory|folder

`git remote add origin ?`: Assigns the keyword `origin` to the remote repository

`git status`: Obtains the current status of your local repository
- shows tracked files that CRUD has been performed upon

`git add .` : Adds all files in given directory to the staging environment for GH

`git commit -m "?"`: Sets up a new commit with a custom message which is represented by the ?

`git push origin ?`: Pushes the staged commit from your branch(?) to the remote repository, where origin is the url of the repository referenced by running command above (1)

`git pull origin ?`: Pulls the latest commits from the remote repository branch(?), where origin is the url of the repository referenced by running command above (1)

`git branch -a` : Shows all branches in the local and remote repositories

`git branch -d ?` : Deletes the named branch from local repository, where ? is the name of the branch

`git push origin --delete ?` : Deletes the named branch from remote repository, where ? is the name of the branch

`git reset HEAD~` : Resets the local branch state back to its original state (1 commit back) as indicated by remote

`git reset HEAD~?` : Resets the local branch state back a certain number of commits 

`git remote prune origin` : Deletes branches in local repository already deleted in remote repository

`git stash` : Saves working files and changes not committed into stack

`git stash list` : Lists all stashes on the stack in order

`git stash pop` : Applies the stash based on the top of the stack

`git stash drop` : Discards the stash from the top of the stack

`git apply stash` : Applies the last saved stash to the given workspace on the given local branch

`git clean -n` : Performs a dry run of the clean command given to Git CLI 

`git checkout ?` : Moves the current HEAD to the specified branch, where ? is the branch

`git checkout master` : Moves the current HEAD to the master branch

`git checkout -b ?` : Creates a new branch and moves the current HEAD to the specified branch, where ? is the branch

`git log --oneline` : Logs the commits for the local repository from all branches in a nice format

`git clone ? .` : Clones the remote repository and renames the folder in which its contents are stored, where ? is the url of remote repository to be cloned and . is the name of the folder the contents are stored in

`git rebase -i ?` : Rebases the current local repository based on certain commit SHA, where ? is the SHA of the commit/branch. Useful to squash, drop, edit, commits before pushing them to the remote repository to make a PR

`git add .; git commit --amend` : Usually utilized when small update is made after the commit has been committed. Useful to add aforementioned smaller change to the commit just gone



# Docs

[Freecodecamp: git merge and rebase](https://www.freecodecamp.org/news/the-ultimate-guide-to-git-merge-and-git-rebase/)

[SO: reverse applying a stash](https://stackoverflow.com/questions/1020132/how-to-reverse-apply-a-stash)