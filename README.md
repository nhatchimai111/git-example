# GIT Command


###  1. Import a new project
>$ git init <project_name>
<Enter>
### 2. Include in what will be committed OR Update what will be committed

- 2.1 Add a file to staging
>$ git add <path/to/file>

- 2.2 Add a folder to staging
>$ git add <path/to/folder>

- 2.3 Remove a file to staging
>$ git rm <path/to/file>

- 2.4 Add all files to staging
>$ git add .

### 3. Show status
>$ git status

### 4. Commit with log
>$ git commit -m <Message>

### Change commit log
>$ git commit --amend -m <Message>

### 5. Show log
>$ git log

>$ git log --oneline

### 6. Revert to commit_id
>$ git checkout <commit_id>

>$ git revert <commit_id>

### 7. Switch branch
>$ git checkout <branch_name>

### 8. Discard changes in working directory
>$ git checkout -- <file>

### 9. Create branch
>$ git branch <branch_name>

### 10. Show all branch information
>$  git branch -a

### 11. Delete branch
> $ git branch -d <branch_name>

> $ git branch -D <branch_name>

### 12. Merge branch
> $ git merge <branch_name>

### 13. Create new branch from current branch
>$ git checkout -b <branch_name>

### 14. Rename current branch
>$ git branch -m <new_name>

### 15. Merge upcomming branch into current branch
>$git merge <upcomming_branch>

### 16. Fetch latest upstream branches
>$git fetch <upstream_remote>


### 17. Commit with message
>$ git commit -m <message>

### 18. Add upstream
>$ git remote add <upstream_remote> <link_to_upstream_repository>

### 19. Remove remote upstream
>$ git remote remove <upstream>

### 20. Reset to a commit via commit code
>$ git reset —hard <commit_code>

### 21. Reset to latest commit
>$ git reset —hard

### 22 Reset file to unstage
>$git reset HEAD <file>

### 23. Pull code from remote repository
>$ git pull

### 24. Push to remote repository branch develop
>$ git push origin <develop>

### 25. Force-push origin repository branch develop
>$ git push origin develop -f 

### 26. Set public user name
>$ git config --global user.name <your_name>

### 27. Set public email
>$ git config --global user.email <your_email>

### 28. rebase <child_branch> into <master_branch>
>$ git rebase <child_branch>








