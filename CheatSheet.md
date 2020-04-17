# Git CheatSheet

## Make a new folder (aka make directory)
mkdir <FOLDERNAME>

## Navigate into an existing folder (aka change directory)
cd <FOLDERNAME>

## List the items in a folder
ls

## Turn Git on for a folder
git init

## Check status of changes to a repository
git status

## View changes to files
git diff

## Add a file's changes to be committed
git add <FILENAME>

## To add all files changes
git add

## To commit (aka save) the changes you've added with a short message describing the changes
## git commit -m "your commit message"
## You can create and switch to a branch in one line
git checkout -b <BRANCHNAME>

## Create a new branch
git branch <BRANCHNAME>

## Move onto a branch
git checkout <BRANCHNAME>

## List the branches
git branch

## Rename a branch you're currently on
git branch -m <NEWBRANCHNAME>

## Verify what branch you're working on
git status

## Check Git status
git status

## Pull in changes from a remote branch
git pull <REMOTENAME> <REMOTEBRANCH>

## See changes to the remote before you pull in
git fetch --dry-run

## Merge a branch into current branch
git merge <BRANCHNAME>

## Change the branch you're working on
git checkout <BRANCHNAME>

## Delete a local branch
git branch -d <BRANCHNAME>

## Delete a remote branch
git push <REMOTENAME> --delete <BRANCHNAME>

## Pull from a remote branch
git pull <REMOTENAME> <BRANCHNAME>
