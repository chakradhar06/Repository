## Cloning
git clone https://github.com/chakradhar06/demo <br>
git clone --branch br https://github.com/chakradhar06/demo

## Logging In Commands
git config --global user.name chakradhar06
git config --global user.email chakrivanarasi@gmail.com

## Basic Commands
git init
git add file_name (git add .   //to add the whole folder)
git status

git commit -m "first commit"
git commit -m "first commit" file_name

git log // shows logs on that branch only
git log --oneline

git remote add origin https://github.com/chakradhar06/demo.git  (git remote -v // to check)
git remote set-url origin https://github.com/chakradhar06/demo.git  (git remote -v // to check)

git push -u origin main
git push --set-upstream origin main
git pull // to get the added files from the repo to local

## Branching & Merging Commands
git branch // for checking the branches
git branch chakri // for creating a new branch
git branch -M main // for renaming the branch on the branch you are
git branch -d chakri // for deleting the branch with name - 'br'
git checkout master // for shifting into the branch - 'main' 
git merge chakri // for merging the chakri branch into master 
