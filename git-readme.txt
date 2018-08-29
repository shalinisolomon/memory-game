==========================
>>>>>>>GIT HACK<<<<<<<<<< 
==========================

Steps
---------------
1. git init - this command will initialise your local/ current folder as a git repository.

2. git status -  shows the current files / folders that are under modification.
              -  Also hilight's tracked and untracked files

3. git add - Adds the file to repository
    Example  >>>>>    git add Index.html -  add's only Index.html file
    Example  >>>>>    git add . -  add's all the untracked files to repository

===================================
How to publish code to Git - Server
===================================
 Git follows 2, mostly 3 steps to push changes to Server
 :: commit
 :: get latest from Server
 :: resolve conflicts
 :: publish your final changes

 >> Scenario 1 : If only one user/ contributor. Follow this
    {*}==> git commit -m "ENTER YOUR MESSAGE"
    { }==> git remote add origin https://github.com/shalinisolomon/memory-game.git
    {*}==> git push
    { }==> git push -u origin master [DO THIS ONLY FIRST TIME AFTER STEP 2]

****** Simplified *****
1. git commit -am "ENTER COMMIT MESSAGE"
2. git pull --rebase
3. git push

