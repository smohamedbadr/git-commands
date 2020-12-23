#GIT Commands

Welcoming you!!!
git --version

create a local folder "git-checkout"

cd folder path

git clone "remote repo path"

cd "local repo path"

git status

just open the read me file and add some text and then

git pull

git status

modify the same read me file in your local 

git status

git add README.md (either u may can use add . or add, add - for single file and add . for adding multiple files)

git status

git commit -m "updated read me file"

git push origin main

git checkout -b feature/git-workarround-feature

git push origin feature/git-workarround-feature

git checkout main (switch from feature to main)

git branch (will list all the branches on the specific repo)

go to feature/git-workarround-feature branch

made some changes on the read me file

git checkout feature/git-workarround-feature

git status

git add .

git commit -m "updates...."

git push origin feature/git-workarround-feature

Git Pull Request:

push all your changes to your feature/git-workarround-feature branch

Go to repo and raise a PR request to merge your changes to the main repo

The changes from the feature will be reviewed and merged to the main/master branch

Resolving Conflicts:
go to repo main and edit the read me file and add some lines and commit
come to your feature/git-workarround-feature branch and add some other lines at the same line numbers and add the changes
now try to checkout the main branch
you will get an error says please commit your changes before switch to other branches
commit your changes
while pushing you will get error says that pull first
pull the latest from the main, will inform about the conflicts, we have to fix it locally and push our code to the remote repo.
git diff will help you out to see the diff between two branches, means your current and the remote.
git merge master -  from your branch to master.
=============
GIT INIT:

create a folder in your local and the create a readme.md file and add and commit in your local repo

git init

git add . 

git commit -m "added README.md file 

go to the repo and create a new repo with the same name as in local

git remote add origin remote repo path
git push local repo


GIT UNDO

update read me file
git log

git reset given hashcode (soft reset)

git reset --hard hashcode (hard reset), changes will be reverted back

