# COMMANDS FOR GITHUB FOR ME


## COMMANDS :

    __git init__ - (create new emty local repository)

    git status - (show status of repository)

    git add *name of file* - adding file in repository
    git add -A -(add ALL files)

    git commit -m "*commit*" - add commit (first commit named 
    *Initial commit*)
    git commit -amend -m "**" -(change commit)

    git log  -(history of changes FULL)
    git log --oneline    -(history of changes small)
    git log --oneline --all    -(history of changes ALL)

    git checkout *hash*    - (join commit)
    git checkout main - (join last commit main commit)

    git remote -v  -(watch the remote(удаленны) repository)
    git remote add origin *SSH* (add remote repository to folder)

    git push -u origin main  -(send files to the remote repository)
    


## CREATE NEW LOCAL REPOSITORY:

    git init
    git status
    git add *file*
    git commit -m "Initial commit"


## SAVE CHANGES:

    git add *file* - file with changes
    git commit -m "Commit changes"


## JOIN SOME COMMIT

    git status   -(open hashes)
    git checkout *hash* 


## CREATE REMOTE REPOSITORY TO FOLDER

    git remote add origin *SHH*
    git remote -v
    git push -u origin main


