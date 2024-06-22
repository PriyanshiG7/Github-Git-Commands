#Git Commands

A list of my commonly used Git commands


#Getting & Creating Projects
__Command__	                                                                                      __Description__
git init                                                                                      | Initialize a local Git repository
git clone ssh://git@github.com/[username]/[repository-name].git                               |	Create a local copy of a remote repository


#Basic Snapshotting
__Command__	                                                                                       __Description__
git status	                                                                              | Check status
git add [file-name.txt]                                                                       | Add a file to the staging area
git add -A	                                                                              | Add all new and changed files to the staging area
git commit -m "[commit message]"                                                              |	Commit changes
git rm -r [file-name.txt]                                                                     |	Remove a file (or folder)


#Branching & Merging
__Command__	                                                                                      __Description__
git branch	                                                                              | List branches (the asterisk denotes the current branch)
git branch -a	                                                                              | List all branches (local and remote)
git branch [branch name]	                                                              | Create a new branch
git branch -d [branch name]	                                                              | Delete a branch
git push origin --delete [branch name]                                                        | Delete a remote branch
git checkout -b [branch name]	                                                              | Create a new branch and switch to it
git checkout -b [branch name] origin/[branch name]                                            | Clone a remote branch and switch to it
git branch -m [old branch name] [new branch name]	                                      | Rename a local branch
git checkout [branch name]                                                                    |	Switch to a branch
git checkout -	                                                                              | Switch to the branch last checked out
git checkout -- [file-name.txt]	                                                              | Discard changes to a file
git merge [branch name]	                                                                      | Merge a branch into the active branch
git merge [source branch] [target branch]                                                     |	Merge a branch into a target branch
git stash                                                                                     |	Stash changes in a dirty working directory
git stash clear	                                                                              | Remove all stashed entries


#Sharing & Updating Projects
__Command__	                                                                                      __Description__
git push origin [branch name]                                                                | Push a branch to your remote repository
git push -u origin [branch name]                                                             | Push changes to remote repository (and remember the branch)
git push                                                                                     | Push changes to remote repository (remembered branch)
git push origin --delete [branch name]                                                       | Delete a remote branch
git pull                                                                                     | Update local repository to the newest commit
git pull origin [branch name]                                                                | Pull changes from remote repository
git remote add origin ssh://git@github.com/[username]/[repository-name].git                  | Add a remote repository
git remote set-url origin ssh://git@github.com/[username]/[repository-name].git              | Set a repository's origin branch to SSH


#Inspection & Comparison
__Command__	                                                                                       __Description__
git log	                                                                                      | View changes
git log --summary                                                                             |	View changes (detailed)
git log --oneline                                                                             |	View changes (briefly)
git diff [source branch] [target branch]                                                      |	Preview changes before merging



| Command | Description |
|---|---|
| git init | Create a Git repository |
| git clone <url> | Clone an existing repository |
| git branch | List branches |
| git checkout <branch name> | Switch branches |
| ... (add more commands and descriptions) | ... |
