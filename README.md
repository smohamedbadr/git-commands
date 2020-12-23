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
go to the main repo and edit the read me file and add some text and commit the changes
back to your local repo and add some text in your local read me file  and then add and commit your local changes
try to push your local changes to the remote repo you will be getting an error says that take a pull before push
whilte pulling the changes from your remote repo it will try to merge it's own changes to your local read me file
if there won't be conflicts then merge will be done without any issues. if there is any conflicts then that needs to be taken care
open the file and see the revisions, HEAD is your local changes and the other changes would comes from the remote repo
either you may revert your changer or remote or you can manually merge all your changes with remote. once the merge done 
your local will be sync with the remote repo. now do git status and push your local changes to remote.

git push local to remote - issue
git pull origin remote repo
git diff
git merge 
git status
git push origin remote repo
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

