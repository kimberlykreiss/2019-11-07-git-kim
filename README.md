# DCR 2019 Git Workshop 

Git workshop for DCR 2019 

## Local 

- `init`: initialize folder as git repo
- `status`: see what is going on in the repo 
- `add`: put file(s) into staging area 
- `commit`: commit files from staging area 
- `diff`: see the changes that were made between different files. git diff --staged shows what's different after files are staged 
- git diff HEAD~2 (show the differences between current and two commits ago) 
- `checkout`: move your `HEAD` around 
- `HEAD`: where you are currently looking at in history 
- `log`: looking at all your previous messages 
	- `log --oneline`: get a one line representation of history 

# Remotes
- `remote`: somewhere your git repo is stored (eg, Github)
	`origin`: the default you give your remote
- `push`: sending local changes to remote 
- `pull`: receiving changes from remote 

# Notes 

- git config --list (shows your configs)
ls -al (list all hidden files in this folder) 
nano README.md

git add . vs git add --all 
git add . is everything in this folder and down 
git add --all is everything in the repo 

## Branches 

- `branch <branch-name>: create a new branch 
- `checkout <branch-name>`: move to that branch 
- `checkout -b <branch-name>`: create and move at the same time 
- `branch -a`: see what branches we have 

- `log --oneline --graph --decorate --all`: what is going on?
  - This is a diagram 




