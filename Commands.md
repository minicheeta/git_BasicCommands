
# Basic git command and instruction

## Create repository
- **git init** -- creating a new Git repository in the current directories

## Adding files to tracking
- **git add <file name>** -- add a specific file to the index (staging area)
- **git add .** -- add all changes in the current directory to the index

## Fixate changes
- **git commit -m "message"** -- commit changes with comment

## Stats checking 
- **git status** -- current status of files in repositories

## Commit history
- **git log** -- show commit hhistory

## Contacting a remote repository
- **git remote add origin <URL>** -- add a remote repository
- **git push -u origin main** -- push changes to the "main" branch

## Send changes
- **git push** -- send committed changes to the remote repository



## Branches
- **git Branch** -- show the list of branches 
- **git Branch <branch_name>** -- create a new branch
- **git checkout <branch_name>** -- switch to a branch
- **git merge <branch>** -- merge the specified branch from the current moment