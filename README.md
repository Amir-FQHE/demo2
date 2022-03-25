# demo 2



Some description!

## subHeader


context

in git bash

git pull https://github.com/Amir-FQHE/demo.git 
*take github repository and put in current directory*


git status 
*see status of files *


in git bash

git add . *add all files*

git commit -m "message" -m "submessage" *will commit changes*

git push *this will add the local repository changes to github respoitory*

_________________________________________________________________________

to add a directory on machine to github do

git init

git add .

need to create a new repository on github

git remote add origin https://github.com/Amir-FQHE/demo2.git

connect local repository to github repository

git remote -v
*shows repositorys that are connected*


git push -u origin master
echo "# demo2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Amir-FQHE/demo2.git
git push -u origin main

to create a branch

git branch *to see all branches and current branch *

git chekout -b branchname *create a new branch*

git checkout branchname *to switch to a different branch*
