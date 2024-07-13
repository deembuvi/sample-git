# Git Commands

In this repo I'll add some basic commands for using Git:
```sh
  git init #initializes git repo
  git add . #adds another file
  git commit -m "Initial commit" #commits changes added
```
> The above commands are used to initialize, add and commit git changes to a repo.

Below are the commands used in deploying to GitHub:
```sh
  git remote add origin <insert GitHub URL or SSL> #adds a remote URL repo as our origin
  git push -u origin main #assuming the main branch is "main" if not, change to master
```

### Utility Git Commands 
```sh
  git status #checks the files that need to be committed
  git branch #checks the branches that are available
  git branch -M main #changes the main branch name from master to main
```
### Sync with remote repo
```sh
  git pull #pulls changes from remote repo
```
