Git clone - to copy or clone the project from web onto your local memory
Git log - to check all the commits
Ls - check all directories
Rm -rw projectname - remove the project from directory
Git remote -v - to check whose repository it is after forking
Git init - create git in a folder
ls -la :see inside a folder
Git status - check commits
Vim LICENSE - to create license file
i - to insert license
Esc - to save license
:wq - save and quit vim
Git add LICENSE - include changes in license file from next commit onwards
Git commit -  to save progress in git
Git config --list : list all configurations set
Git config user.name “ your name” - set ur name
Git config user.email “your email”
Git config --local --list : list all local configurations set
Git config --global --list : list all global configurations set
git remote -vv : See all the remotes currently set up
git remote add origin <url> : Add ur project on GIT Repo
git push —set-upstream origin master : Push local code on git repo
git add .  Add little changes
git commit -m “Your Commit Message”
git push : push your commit
git diff : to see the changes u maid
touch filename/.keep : create an empty file
git add tutorials/* : add any file inside tutorials directory
git diff --staged : to see diff in staging area and main area
git reset HEAD "path/filename" : undo change maid[git add is reset]
git add -i : shows all files that are modified and whether or not if they r staged
mv <folder/filename> <folder>
git reset HEAD .   : Reset last change
git checkout -- .   : Cancel deletion of file when it is moved from folder to folder
rm <folder/filename> : Delete file
git mv <folder/filename> <folder> : move file from one folder to another n checked in git
git rm <folder/filename> : delete file in git
vim .gitignore : to create git ignore file
inside git ignore - *.html : to ignore allhtml files in that directory
git log --oneline : see all logs in one line
git log --graph : graph representaton
git log -p : commit summary
git shortlog
git log --author="author name" : search commits by author name
git log --grep="idea" : search commits by commit msgs
git log -- README.md : search by file name
git log -S"[x]" -p : to check where the todo item was checked off
git log -- books : see all commits made in books folder
git log -p --all -S"Windows 10" : see all commits in which windows 10 was used