# COMMANDS FOR GITHUB FOR ME


## COMMANDS :

    git init - (create new emty local repository)

    git status - (show status of repository)

    git add *name of file* - adding file in repository
    git add -A -(add ALL files)

    git commit -m "*commit*" - add commit (first commit named 
    *Initial commit*)
    git commit -amend -m "**" -(change commit)
    git commit -a -m "*commit*" -(add+commit)

    git log  -(history of changes FULL)
    git log --oneline    -(history of changes small)
    git log --oneline --all    -(history of changes ALL)
    git log *branch* --oneline   -(history of changes in corrent brunch)

    git checkout *hash*    - (join commit)
    git checkout main - (join last commit main commit)

    git remote -v  -(watch the remote(удаленный) repository)
    git remote add origin *SSH* (add remote repository to folder)

    git push -u origin main  -(send files to the remote repository)
    git push -u origin *branch*  -(send files to the remote repository from current branch)  
    git push   - (you can use at second time)

    git clone *SHH*    - (clones somebodys repository to your computer)
    git clone *SHH* *folder*    - (clones somebodys repository to your computer and create folder)

    cd *folder* - (change directory) cd folder2 (for example)
    cd ..  -(back to folder up)
    cd ...   -(go to dekstop)

    git branch - (check branches)
    git branch *new-branch*  - (create a new branch)
    git checkoout *branch*  - (join branch)
    git checkout -b *new-branch* - (create and join new branch)

    git merge *branch* -(merge branches (объеденить ветки, должен находиться в ветке в которую объеденяешь))

    git pull    - (update (take changes) from online repository)
    then ESC :wq

    git revert *hash* (correction or deletion coomit)



## CREATE NEW LOCAL REPOSITORY:

    git init
    git status
    git add *file*
    git commit -m "Initial commit"


## SAVE CHANGES:

    git add *file* - file with changes
    git commit -m "Commit changes"
        or
    git commit -a -m "*commit*"

## JOIN SOME COMMIT

    git status   -(open hashes)
    git checkout *hash* 


## CREATE REMOTE REPOSITORY TO FOLDER

    git remote add origin *SHH*
    git remote -v
    git push -u origin main



## CLONE SOME PROJECT FROM GITHUB

    git clone *SHH*
    cd *directory of clone*


## CREATE NEW BRANCH

    git branch *new-branch*
    git checkoout *branch*
    git branch
        or
    git checkout -b *new-branch*


## CHANGE OR DELETE COMMIT

    git log --oneline
    git revert *hash*
    git push -u origin main


# .gitignore

Creating in main folder


folder/  (ignore folder)
*.md (ignore all files .md)