## Cloning
git clone https://github.com/chakradhar06/demo <br>
git clone --branch br https://github.com/chakradhar06/demo <br>

## Logging In Commands
git config --global user.name chakradhar06 <br>
git config --global user.email chakrivanarasi@gmail.com <br>

## Basic Commands
git init <br>
git add file_name (git add .   //to add the whole folder) <br>
**git status** <br>

git commit -m "first commit" <br>
git commit -m "first commit" file_name <br>

git log (shows logs on that branch only) <br>
**git log --oneline** <br>

git remote add origin https://github.com/chakradhar06/demo.git  (git remote -v // to check) <br>
git remote set-url origin https://github.com/chakradhar06/demo.git  (git remote -v // to check) <br>

git push -u origin main <br>
git push --set-upstream origin main <br>
git pull (to get the added files from the repo to local) <br>

## Branching & Merging Commands
git branch (for checking the branches) <br>
git branch chakri (for creating a new branch) <br>
git branch -M main (for renaming the branch on the branch you were) <br>
git branch -d chakri (for deleting the branch with name - 'br') <br>
git checkout main (for shifting into the branch - 'main') <br>
git merge chakri (for merging the chakri branch into main) <br>

## Undoing Changes and Recovering from Mistakes in Git
git restore <file_name> (Undo Changes in the **Working Directory**) <br>
git restore --staged <file_name> (Unstage Files from the **Staging Area**) <br>
git reset --soft <commit_hash>(or)HEAD\~1 (**Undo a Commit** Without Losing Changes - Removing commits till that hash) <br>
git reset --hard <commit_hash>(or)HEAD\~1 (**Undo a Commit** and Discard Changes - Removing commits till that hash) <br>
git revert <commit_hash> (Revert a Commit Without Changing History - Removing any middle commit) <br>



