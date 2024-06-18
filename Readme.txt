1.  'git init'  -->  powers  your folder to be managed by git  and initalises a new empty repository.IIt also ccreates a .git folder 
that has all  the relevant logic to manage  versions of your project.

2.  'working area'  -->  There can be a bunch of files that are not currentlu handled by git. It means that changes done or to be done
in those files are not managed by git yet. A file which is in working area is cconsiderd to be not in the staging area. when we do 'git status;
and we see abunch if 'untracked files' then these are actually called to be in the working area.

3.  'staging area'  -->  What all files are goinng to be part of the next version that we will create. this staging area is the place where git
knows what changes will  be done from the last version to the next version.

4.  'Repository Area'  -→  This area actually contains the details of all you previous registered version. And the files in this area, git already
 manages them and knows their version history.

5.  'git add <file>'  -->   moves file from working area to staging area.

6. 'git rm-cached <file>'  -->  moves file back from staging area to working area.


7. 'commit'  -->  Commit is a particular version of the project. It captures a snapshot of the project's staged changes and creates a version 
out of it.

8. 'git commit'  -->   registers staging changes to a commit.


