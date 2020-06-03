# GitHub-Commands
All common github commands

* Clone branh to local  
`git clone`

* Show all loacl branches  
`git branch`

* Create new branch  
`git checkout -b your-branch-name`

* Stage the file for commit to your local repository  
`git add .`

* Commit  
`git commit -m "your commit message"`

* Push to active branch  
`git push`

* Push at new branch   
`git push --set-upstream origin your-branch-name`

* Push your branch to the remote repository  
`git push -u origin feature_branch_name`

* Reset file to Master changes  
`git checkout master  "your-file-name.js"`

* Rename branch  
`git push origin :old-name-of-branch-on-github`  
`git branch -m old-name-of-branch-on-github new-name-for-branch-you-want`  
`git push origin new-name-for-branch-you-want`

* The command to list all branches in local and remote repositories is  
`git branch -a`

* Delete a branch  
`git branch -d branch-Name`

* Status Active branch and commit status  
`git status`

* Add all files to a commit except a single file  
`git add -u`  
`git reset -- your-file-path`

* Git merge master into the branch  
`git checkout your-branch-name`  
`git merge master`  

