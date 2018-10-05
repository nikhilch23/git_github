## What is GitHub?

1. What are remotes?

	* Upstream
	* Origin

2. What is a local repo?


## How does GitHub work?

1. It is a good habit to first fork the original repo and then clone it to the local computer.
2. Once the work is done on the local repo, we push to the remote (origin).
3. Then a PR is sent to the upstream. PR is a request that see through my code, if you are satisfied enough, please merge it to your code.

###  Basic workflow of GitHub:

1. First fork the original repo to your own github account. This process is called **Forking**.
	* Here is the url of the original repo.  https://github.com/kossiitkgp/sandbox-2018
	* First fork this.


2. Now we will clone the repo to our local computer. This process is called **Cloning**.  `git clone <url>`

3. `git remote -v`  : this gives the info of my remote repo
	`git remote add upstream <url>` : This will link the upstream to our local repo.

	Do `git remote -v` again. Now we can see the origin as well upstream added.

3. `git branch -a` : Gives the list of branches in our repository.


4. Now we will add a txt file to our repository. 

5. `git status`  : We can see the result and infer from that.

6. `git add .`   : Once we do git add, the changes are sent to the staging area.

https://imgur.com/FBog3NW   : Here it describes how the staging area works

7.
* `git reset <filename>`  : Removes the file from the staging area
* `git reset` : Removes everything from the staging area as untracked file.

8. `git add .`

9. `git commit`

10. `git diff <commit1> <commit2>`:  Gives the difference between the two commits.

11. `git pull origin master` : Always do this before pushing beacuse there might be more than one contributors. This will update the local repo in case any changes have been made.

12. `git push origin master` : This pushes the changes on the local computer to the origin.


* `git commit -m ".....message"`


* `git log` : Gives the commits list



### Common workflow

* `git branch xyz`

* `git branch`: asterisk beside the branch name implies the current branch

* `git checkout xyz`

* `git push origin xyz` : We have pushed xyz branch to the remote origin.

* `git checkout master`

* `git pull origin master`

* `git merge xyz`

* `git push origin master`


* `git branch -d xyz` : Deletes the local branch

* `git push origin --delete xyz`  : Deletes the branch on the remote as well.

* `git branch -a`


### Sending a PR:

* Now you must have pushed your changes to the remote origin.
* Go to the  origin and send a PR from there.


