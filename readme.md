# Git and Github Rules.
Git 
remember to add git lense to VSCODE

git config --global user.name(or email) "name or email" 

git config --global core.editor "code --wait"(using VSCODE)

git --version
git status
git init
git add
git commit
git push - move to cloud
touch
pwd
git commit -m "xxxxxxxx"
git log --oneline
.gitignore("to ignore files")
git branch
gitignore generator
git branch nav-bar
git checkout nav-bar or git switch nav-bar
git merge nav-bar
git branch -d nav-bar - delete branch
git checkout -b footer (create and switch branch)

git diff --staged
git diff commitid1 commitid2
git diff branchone branchtwo

git stash
git stash pop - undo the stash
git stash list - list of stash
git stash apply stash@{0}- get a particular stash

git checkout <logid> - to check previous commit

git reflog - moves HEAD to previous or git master to return.

git checkout HEAD~2 - moves two commit back

Git Rebase - Do not run from the master or main branch, only run from side branch
eg. git rebase master


SETTING UP GITHUB
create account and login
setup ssh using git doc

git branch -M main

git remote add origin https://github.com/EmmanuelIzu/learngit.git

git remote -v

git push -u origin main 

git push --set-upstream origin sec_branch

readme.md

git clone url

git fetch

git pull 
