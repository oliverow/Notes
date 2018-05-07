# Git cheat sheet
## Three main areas
Working Directory, Staging Area, Repository

## Command Lines
`git add`
add finished file from working directory to staging area

`git commit`
move new changes from staging area to repository
`git push`

`git checkout`
revert staged files to its original version

`git reset`
undo `git add`

`git revert HEAD`
undo `git commit`
`git revert HEAD~n..HEAD`
undo n-th `git commit`

`git init`
initialize a git working directory

`git remote add origin <url>`
add remote url to git config

`git push`
push commits to remote repo
`git push -u origin master`
set upstream url

`git clone <url>`
clone remote git repo

`git pull`
pull new changes from remote git repo
