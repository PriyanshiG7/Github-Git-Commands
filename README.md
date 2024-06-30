#Comman Github Command 

## Basic Syntax

| Command Name| using way |
|---|---|

|### Heading| # H1
              ## H2
              ### H3|



|### Bold| **bold text**|



|### Italic|*italicized text*|



|### Blockquote|> blockquote|



|### Ordered List|1. First item|
                  2. Second item|
                  3. Third item|

|### Unordered List|- First item|
                    - Second item|
                    - Third item|

|### Code| `code`|

|### Horizontal Rule| --- |

### Link

[Markdown Guide](https://www.markdownguide.org)

### Image

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight

I need to highlight these ==very important words==.

### Subscript

H~2~O

### Superscript

X^2^





















#Git Commands

A list of my commonly used Git commands


#Getting & Creating Projects
|__Command__	                                                                                     | __Description__|
|---|---|
|git init                                                                                      | Initialize a local Git repository|
|git clone ssh://git@github.com/[username]/[repository-name].git                               |	Create a local copy of a remote repository|


#Basic Snapshotting
|__Command__	                                                                                       |__Description__|
|---|---|
|git status	                                                                                   | Check status|
|git add [file-name.txt]                                                                       | Add a file to the staging area|
|git add -A	                                                                                   | Add all new and changed files to the staging area|
|git commit -m "[commit message]"                                                              |	Commit changes|
|git rm -r [file-name.txt]                                                                     |	Remove a file (or folder)|


#Branching & Merging
|__Command__	                                                                                     | __Description__|
|---|---|
|git branch	                                                                                       | List branches (the asterisk denotes the current branch)|
|git branch -a	                                                                                   | List all branches (local and remote)|
|git branch [branch name]	                                                                         | Create a new branch|
|git branch -d [branch name]	                                                                     | Delete a branch|
|git push origin --delete [branch name]                                                            | Delete a remote branch|
|git checkout -b [branch name]	                                                                   | Create a new branch and switch to it|
|git checkout -b [branch name] origin/[branch name]                                                | Clone a remote branch and switch to it|
|git branch -m [old branch name] [new branch name]	                                               | Rename a local branch|
|git checkout [branch name]                                                                        |	Switch to a branch|
|git checkout -	                                                                                   | Switch to the branch last checked out|
|git checkout -- [file-name.txt]	                                                                 | Discard changes to a file|
|git merge [branch name]	                                                                         | Merge a branch into the active branch|
|git merge [source branch] [target branch]                                                         |	Merge a branch into a target branch|
|git stash                                                                                         |	Stash changes in a dirty working directory|
|git stash clear	                                                                                 | Remove all stashed entries|


#Sharing & Updating Projects
|__Command__	                                                                                |     __Description__|
|---|---|
|git push origin [branch name]                                                                | Push a branch to your remote repository|
|git push -u origin [branch name]                                                             | Push changes to remote repository (and remember the branch)|
|git push                                                                                     | Push changes to remote repository (remembered branch)|
|git push origin --delete [branch name]                                                       | Delete a remote branch|
|git pull                                                                                     | Update local repository to the newest commit|
|git pull origin [branch name]                                                                | Pull changes from remote repository|
|git remote add origin ssh://git@github.com/[username]/[repository-name].git                  | Add a remote repository|
|git remote set-url origin ssh://git@github.com/[username]/[repository-name].git              | Set a repository's origin branch to SSH|


#Inspection & Comparison
|__Command__	                                                                                   |    __Description__|
|---|---|
|git log	                                                                                     | View changes|
|git log --summary                                                                             |	View changes (detailed)|
|git log --oneline                                                                             |	View changes (briefly)|
|git diff [source branch] [target branch]                                                      |	Preview changes before merging|


#Fixing Mistake
|__Command__	                                                                                   |    __Description__|
|---|---|
|git commit --amend	                                                                           | You forgot to add files or made a minor error in the last commit message.|
|git revert <commit>                                                                            |	Merging branches with conflicting changes.|
|git commit (new commit) + git rebase -i HEAD~<n>                                              |	You want to fix a typo in a commit message that's not the last one.pen_spark.|
|git reset <filename>                                                                           |for managing the staging area and file revisions/To unstage a specific file.  |
|git reset                                                                                      | to unstage all file|  
|git reset HEAD~1                                          |without flags) is a mixed reset that moves the HEAD back one commit, discarding staged changes but keeping uncommitted changes.|
|git reset --mixed <commit>                                                                     |To keep working directory changes based on an older commit|
|git reset --hard <commit>                                             |You want to discard all changes made after a specific commit (including staged and unstaged changes).|







