`git init` --> Powers your folders to be mananged by git, and initialize a new empty repository. It also creates a .git folder that has all the relevant logic to manage version of your projects.

`git status`---> to track the status of your project/ Changes in projects


`Working area`---> There can be a bunch of files that are not currently handled by git.
It means that changes done or to be done in those files are not mananged by git yet.

`Staging area`---> To move untracted files from working area to staging area where changes can be seen


`git rm --cached "<FileName" ` --> Remove file from staging area and send it again to working area. It will stop tracking the files

`Repository Area`--> This area actually contains the details of all your previous registered version.
And the files in this area, git already manages them and know thier version history.

`git add <Files>`--> Move files from working area to staging area.

`git rm --cached "<FileName>"`---> move file back from staging area to working area.

`commit`--> It's a particular version of a project. It captures a snapshot of the project's staged changes and create a version out of it.

`git commit`---> registers staging changes to a commit

`git log`--> list down all the commits of the repository


`git restore <file>`--> It remove all file chages from the staging area to be committed. This can be useful, if we write some dirty lines and now  no more want to it. Instead of deleting every changes line by line, we can restore it or you can say restore last clean version of the file.

Difference between rm and git restore
--> If u want to move the whole file back to untracked state, then we do `git rm`, otherwise if we just want to change to be move in 


`git commit -m "Messages" ` --> If we want to avoid text editor likr vim/nano to add commit message we can use this following command

`git remote`--> List down all the remote connection names

Remote connection --> It helps you to link two git repositories for uploading and downloading changes from each otherwise

`git remote add <name of remote> <Link of remote>` --> This command helps you to add a new link to the remote repo and give a name to it

`git remote rm <name of remote>` : This commands delete a remote connections

`git remote rename <olname>`: This command rename the remote connections

`git add <file1> <file2>`-->This command will add multiple file change together in the staging area

`git add . ` --> This command will add all files from working area to staging area


`git pull <r name> <BranchName>`-->Downloadslatest changes from the branch of the 
