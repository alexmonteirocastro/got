# Git Cheatsheet

## Basic Commands

* Initialize a local git repository: `git init` 
    * Creates a .git folder (hidden) 

* Add files to the staging area (index ): `git add <file>`
    * Many files can be added before committing
    * `git add *.html` adds every html file to the staging
    * `git add .` adds all the files to staging

* Remove files from staging: `git rm --cached <file>`
    * `git rm -r --cached .` removes all the files from staging

* Check the status of the working tree: `git status`
    * **Frequently Used!**

* Commit changes in staging: `git commit`
    * Takes the files from the staging and adds it to the local *Git* repository
    * `git commit -m 'comment here'` commits and skips the editing stage **Frequently Used!**

* Push the changes to the remote repository: `git push`
    * **Frequently Used!**

* Pull the latst versions from the remote repository: `git pull`
    * **Frequently Used!**

* Copy a remote repository into the current folder: `git clone`

* Create a branch: `git branch <branch name>`
    * `git branch -av` lists all exisiting branches
    * `git checkout <branch>` switches to another branch

* Merge a branch with the master: `git merge 'branch name'`

* Delete a local branch: `git branch -d <branch name>`

* Add exisitng local repo to remote repo: `git remote add origin <git repo ssh>`
    * after that `git push -u origin master`
