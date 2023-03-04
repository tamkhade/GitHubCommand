1.creating new branch
-git branch <branch>

2.switch from one branch to another branch
-git checkout <branch>

3.create new local branch
-git checkout -b release-latest

Note: origin is the default name of remote

4.Delete branch using below command
-git delete -d release-latest

5.Ater creating branch we need to push this branch to origin
git push -u origin <branch_name>

6.Git status

7.Git add <filename>

8.Git commit -m "msg" Need to add the msg

9.git push to push the code into repo

10.git branch -r to list the branches.

11.The -am along with the command is to write the commit message on the command
line for already staged files.
Command:
git commit -am "Commit message"

12.Git merge is a command that allows you to merge branches from Git. It preserves the
complete history and chronological order and maintains the context of the branch.
git merge <branch_name>

13.Git Fetch only downloads the latest changes into the local repository. It downloads
fresh changes that other developers have pushed to the remote repository since the
last fetch and allows you to review and merge manually at a later time using Git
Merge. As it doesn’t change the working directory or the staging area, it is safe to use.