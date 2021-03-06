----------------
# GITHUB COMMANDS:
----------------

Username: 	ANTZ411  
Password:	(cap)-------a4--

Username: 	ANTZ314  
Password:	--------aPi3

==============================================================================  
#### file.md:
==============================================================================  
$ markdown_edit  
$ markdown_edit README.md  
$ markdown_edit -f readme.html README.md

#### [Cheatsheet:](https://github.com/tchapi/markdown-cheatsheet/blob/master/README.md)

---------------------------------------
[GITHUB Tutorial:](http://rogerdudler.github.io/git-guide/)  
[POUWH Repo](https://github.com/Antz411/POUWH.git)


----------------------------
#### Upload a new folder to Repo:
----------------------------
create a new repository:  
$ git init

Adds all in the folder:  
$ git add .

Commit all:  
$ git commit -m "comment"

Add the repo origin:  
$ git remote add origin https://github.com/AntzXXX/PATH.git

Push all the files to the new Repo:  
$ git push -u origin master

----------------------------------
#### Upload existing files to new repo:
----------------------------------
Add the repo origin:  
$ git remote add origin https://github.com/AntzXXX/PATH.git

Push all the files to the new Repo:  
$ git push -u origin master

---------------------------------------------------------------------------------
#### Cloning an existing Repo to new folder:
---------------------------------------
create a new repository:  
$ git init

create a working copy of a local repository:  
$ git clone /link/to/repository  
$ cd path/to/git/folder  
$ git status

-----------------------------------------------------------------------------------------------
#### BRANCHING:
-----------------------------------------------------------------------------------------------
After cloned into empty folder - Go to folder path:

Make sure you have the master (* master):  
$ git branch

Get the latest updates:  
$ git pull origin master				-> git pull https://github.com/Antz411/POUWH.git master

Now create a branch of the latest:  
$ git checkout -b new-branch-name			-> git checkout -b POUWH_Branch

Check that you're now on that branch (* new-branch)  
$ git branch


### Make changes you require!!
==============================

Add the new changes to repo-branch:  
$ git add File_Names.ext				-> git add POUWH_1.X

Check changes:  
$ git status

Commit these changes:  
$ git commit -m "comment"

Push the changes to be available on the repo:  
$ git push origin <branch_name>

Branch is now up to date with the master

------------------------------------------------------------------------- Other commands  
Switch back to master  
$ git checkout master

and delete the branch again  
$ git branch -d feature_x				-> git checkout -b POUWH_Branch

Branch is not available to others unless you push the branch to your remote repository:  
$ git push origin <branch_name>

------------------------------------------------------------------------------------------------
First add the proposed changes (add it to the Index):  
$ git add <filename>		- add specified file  
$ git add *			- ?  
$ git add .			- adds all in the folder  

To add to remote repo (or check origin exists):  
$ git remote add origin https://github.com/Antz411/POUWH.git

Check status:  
$ cd path/to/git/folder  
$ git status

To actually commit (Now the file is committed to the HEAD):  
$ git commit -m "Commit message"

To send those changes (in HEAD) to your remote repository:  
$ git push -u origin master


-----------------------------------------------------------------------------------------------
### UPDATE AND MERGE:
-----------------------------------------------------------------------------------------------
Update your local repository to the newest commit  
$ git pull

To merge another branch into your active branch (e.g. master)  
$ git merge <branch>

Resolve specified conflicts and then mark the changes  
$ git add <filename>

Before merging changes, you can also preview them by using  
$ git diff <source_branch> <target_branch>


-----------------------------------------------------------------------------------------------
### GIT ERRORS:
-----------------------------------------------------------------------------------------------
fatal: 'origin' does not appear to be a git repository  
* git remote -v  
* git remote add origin https://github.com/Antz411/POUWH.git  
* git push origin master  
* git remote remove origin

Fatal: refusing to merge unrelated histories  
* git pull https://github.com/path.git --allow-unrelated-histories


---------------------------------------
[GITHUB Tutorial:](http://rogerdudler.github.io/git-guide/)
[POUWH Repo](https://github.com/Antz411/POUWH.git)
---------------------------------------

----------------------------
#### Upload a new folder to Repo:
----------------------------
create a new repository:  
$ git init

Adds all in the folder:  
$ git add .

Commit all:  
$ git commit -m "comment"

Add the repo origin:  
$ git remote add origin https://github.com/AntzXXX/PATH.git

Push all the files to the new Repo:  
$ git push -u origin master

----------------------------------
#### Upload existing files to new repo:
----------------------------------
Add the repo origin:
$ git remote add origin https://github.com/AntzXXX/PATH.git

Push all the files to the new Repo:
$ git push -u origin master

---------------------------------------------------------------------------------
#### Cloning an existing Repo to new folder:
---------------------------------------
create a new repository:  
$ git init

create a working copy of a local repository:  
$ git clone /link/to/repository  
$ cd path/to/git/folder  
$ git status

-----------------------------------------------------------------------------------------------
#### BRANCHING:
-----------------------------------------------------------------------------------------------
After cloned into empty folder - Go to folder path:

Make sure you have the master (* master):  
$ git branch

Get the latest updates:  
$ git pull origin master				-> git pull https://github.com/Antz411/POUWH.git master

Now create a branch of the latest:  
$ git checkout -b new-branch-name			-> git checkout -b POUWH_Branch

Check that you're now on that branch (* new-branch)
$ git branch

==============================  
--> Make changes you require!!
==============================

Add the new changes to repo-branch:  
$ git add File_Names.ext				-> git add POUWH_1.X

Check changes:
$ git status

Commit these changes:
$ git commit -m "comment"

Push the changes to be available on the repo:  
$ git push origin <branch_name>

Branch is now up to date with the master

------------------------------------------------------------------------- Other commands  
Switch back to master  
$ git checkout master

and delete the branch again  
$ git branch -d feature_x				-> git checkout -b POUWH_Branch

Branch is not available to others unless you push the branch to your remote repository:  
$ git push origin <branch_name>

------------------------------------------------------------------------------------------------
First add the proposed changes (add it to the Index):  
$ git add <filename>		- add specified file  
$ git add *			- ?  
$ git add .			- adds all in the folder  

To add to remote repo (or check origin exists):  
$ git remote add origin https://github.com/Antz411/POUWH.git

Check status:  
$ cd path/to/git/folder  
$ git status

To actually commit (Now the file is committed to the HEAD):  
$ git commit -m "Commit message"

To send those changes (in HEAD) to your remote repository:  
$ git push -u origin master


-----------------------------------------------------------------------------------------------
### UPDATE AND MERGE:
-----------------------------------------------------------------------------------------------
Update your local repository to the newest commit  
$ git pull

To merge another branch into your active branch (e.g. master)  
$ git merge <branch>

Resolve specified conflicts and then mark the changes  
$ git add <filename>

Before merging changes, you can also preview them by using  
$ git diff <source_branch> <target_branch>


-----------------------------------------------------------------------------------------------
### GIT ERRORS:
-----------------------------------------------------------------------------------------------
fatal: 'origin' does not appear to be a git repository  
* git remote -v  
* git remote add origin https://github.com/Antz411/POUWH.git  
* git push origin master  
* git remote remove origin

Fatal: refusing to merge unrelated histories  
* git pull https://github.com/path.git --allow-unrelated-histories

