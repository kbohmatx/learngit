# Common Workflow

1. CREATE a Branch for Feature
    git branch [name]
    git checkout [name]

2. Commit Code
    git add .
    git commit -m"my code"

3. PUSH "BRANCH" to Remote server
    git push -u origin calc-div

4.  Merge Branch with Master.
    git checkout main
    git merge calc-div
    git branch --merged

5. Delete Branch
    git push origin --delete calc-div


