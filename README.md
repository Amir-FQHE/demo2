# demo 2


text

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