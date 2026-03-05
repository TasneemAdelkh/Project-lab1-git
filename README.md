# Project-lab1-git
## Commands used for git
- create local repo and pull the remote repo

    - git init
    - git remote add origin git@github.com:TasneemAdelkh/Project-lab1-git.git
    - git pull origin main
    - git log

- commit the ITI.txt file with my name

    - git status
    - git add .
    - git commit -m "add full name to ITI.txt"
    - git push -u origin main

- add python script with 2 functions and 1 print line to create 3 commits

    - vim lab1.py
    - git add lab1.py
    - git commit -m "add welcome function to lab1.py"

    - vim lab1.py
    - git commit -am "add add function"

    - vim lab1.py
    - git commit -am "print add function result"

- delete the last 2 commits

    - git reset --hard HEAD^^

- add an addition function to create a new commit after deletion

    - vim lab1.py
    - git commit -am "commit after deletion"

- add lab Done at the end of the file and ammend it to the last commit

    - vim lab1.py
    - git commit --amend -m "lab Done"

- add finish and amend the last commit again to "finish"

    - vim lab1.py
    - git commit --amend -m "finish"

- revert the last 2 commits

    - git revert HEAD~2..HEAD

