# My-Repo

Steps :-
(a) First make a main folder and files in which you are working and after doing work, the files will ready to push to GitHub.
    ---> git init
    ---> git add .
    ---> git commit -m "Commit message"
    ---> git log

(b) Now make a remote repository and push the above ready code on it.
    ---> git branch -M main
    ---> git remote add origin "Remote repository link"
    ---> git push -u origin main

(c) Now check branch of your folder
    ---> git branch

(d) Make new branch of this file with the name "Branched-System"
    ---> git branch Branched-System

(e) Now we can switch to the branch from the main
    ---> git checkout Branched-System 
    ---> git branch (// this is used for check that we switch the branch, and this time our "Branched-System" name is show in green colour)

(f) Now we can add another file in which we are working on Branched-System work, And completing our changes to the file.
    ---> git status
    ---> git add .
    ---> git commit -m "Commit message for Changes into branch"
    ---> git push origin Branched-System

(g) Now we are merging the "Branched-System" branch to the main branch
    ---> git checkout main
    ---> git merge Branched-System
    ---> git push -u origin main
    ---> git branch (// this will confirmed that we are merging our branch file to the main successfully)
