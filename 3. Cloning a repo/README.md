# Let's start your journey with Git.

### 1. Creating a local repository. (Git command: git init)
- Simply cd into the directory you want to track and simply type `git init`. This will create a `.git` file in the directory with a basic skeleton without any commits.

### 2. Creating a repository on Github. (Git command: git remote)


### 3. Checking files which can be commited. (Git command: git status)
>`$ git status`

-This will list the files that have been changed in red and those which can be commited in green

- To ignore files create a `.gitignore` file using `touch .gitignore`
- Open this using text editor and add names of files you want to ignore. 

### 5. Staging Area.
- Moving files to staging area:
- For adding files individually use 
> `$ git add <filename>`
- For adding all files at once use 
> `$ git add -A`
- To remove files from staging area use 
> `$ git reset <filename>`
- and to remove all simply type 
> `$ git reset`
### 6. To track the changes you made:
> `$ git diff`
### 7. To commit the files:
> `$ git commit`
- but it is necessary to add messages with the commit to make sure what we did ; so for that we use `-m` extension like `git commit -m “message”`
- You can also the changes you made w.r.t last commit using `git diff <commit>`.If `<commit>` field is kept empty, git will compare it with the last commit.
### 8. To check the commit history:
>` $ git log`
### 9. Branching:
- To create a new branch use `git branch <branchname>`
- To check all the branches present use `git branch`
- To switch over branch use `git checkout <branchname>`
- To do the above processes of creating and switching together use `git checkout -b <branchname>`
- To push a commited changes type in `git push -u origin <branchname>`
- To merge the current branch you are working on to master use `git merge <branchname>`
- To push the changes we simply use `git push origin master`
- To check it they are merged type in `git branch --merged`
- If the branch is successfully merged we can now delete the branch–`git branch -d <branchname>`
