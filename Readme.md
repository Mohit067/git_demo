1.  `git init`  -->  powers  your folder to be managed by git  and initalises a new empty repository.IIt also ccreates a .git folder 
that has all  the relevant logic to manage  versions of your project.

2.  `working area`  -->  There can be a bunch of files that are not currentlu handled by git. It means that changes done or to be done
in those files are not managed by git yet. A file which is in working area is cconsiderd to be not in the staging area. when we do 'git status;
and we see abunch if 'untracked files' then these are actually called to be in the working area.

3.  `staging area`  -->  What all files are goinng to be part of the next version that we will create. this staging area is the place where git
knows what changes will  be done from the last version to the next version.

4.  `Repository Area`  -→  This area actually contains the details of all you previous registered version. And the files in this area, git already
 manages them and knows their version history.

5.  `git add <file>`  -->   moves file from working area to staging area.

6. `git rm-cached <file>`  -->  moves file back from staging area to working area.


7. `commit`  -->  Commit is a particular version of the project. It captures a snapshot of the project's staged changes and creates a version 
out of it.

8. `git commit`  -->   registers staging changes to a commit.

9. `git log`  -->   list downs all commits of the repository.  If you want to exit out of git log prompt press  'q'.

10.  `git restore`  -->   it removes all files changes from the staging area to be committed. This can be useful, if we did some dirty piece  
of cod e and and now  no more want it. Instead of  deleting every change line by, we can say restore last clean version of the file.

11.  `diff between  git rm and git restore`  -->   if you want to move the whole file  back to the  untracked state, then  we do git rm, 
otherwise if we just want  the change to be  moved in area or staging area then we git restore.

12.  `git diff commit1 commit2`  -->   gives the difference of all file changes between two commits.

13.  `git commit -m "<your commit  message>"`  -->   if we want to avoid opening a text editor like vim/nano  to add commit message we can 
use this following command.

14.  `git remote`  -->   list down  all the remote connection names.

15.  `Remote connection`  -->   It helps you to linnk two repositories ffor uploadinng and  downloading  changes from each ohterwise 

16.   `git remote add <name of remote> <link of the remote>`  -->   this  command helps  us to add a new link  to the remote repo and 
give a name to it.

17.  `git remote rm <name of remote>`  -->  this command deletes a remote connection.

18.  `git remote rename <oldname> <newname>`  -->   this command renames the remote connection.


Note : The name of the  remote  connection is always used to estblish connection betweenthe repositories. 


19.  `git add <file1> <file1> <file1>`  -->   This  command will  add multip;le file changes together in the staging area

20.  `git add " . " `  -->   this command will add all file working repo tro  stating are.
 
21.  ` git pull <origin name> <branch name>`  --> download latest change from the branch of the mention remote in your local  repo


