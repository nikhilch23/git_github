![GitHub workflow](https://i.ytimg.com/vi/hSbJaIdqwKg/maxresdefault.jpg)

1. What are remotes?
> A remote in git is a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub or on an internal server. In contrast to a local repository, a remote typically does not provide a file tree of the project's current state.

Popular remotes:

`upstream` generally refers to the original repo that you have forked.

`origin` is your fork: your own repo on GitHub, clone of the original repo of GitHub.


2. What is a local repo?
> The local repository refers to a copy on your own system which you've cloned from GitHub, and also contains the temporary build artifacts that you have not yet released.


## Contribution workflow

1. Fork the repo which you want to make changes but, don't have permissions to do that directly.
2. Clone **your fork** to your computer: `$ git clone <fork-url>`
3. Create a new branch for your feature and checkout the branch: `$ git checkout -b <branch-name>`
4. Make the necessary edits.
5. Compare the edits: `$ git diff`
6. Add your files which you've edited/created to the staging area: `$ git add <file-name>`
7. Commit changes with a message: `$ git commit -m "your message"`

8. Push changes to the origin with your feature branch: `$ git push origin <feature-branch>`

9. Then, it's time to request our changes to the developer of the project. You can do this by sending a Pull Request, which we'll be calling PR from now on.

10. Go to the link of the repository from which you created your fork. Click on Compare and Pull Request. Send it! Pray for the developer to merge that. He might review the PR and request changes. Keep calm and work on your clone. **Remember**: Don't send PRs to your fork. That'll be useless. This is one of the common mistakes that usually happen.





###  Basic workflow of GitHub:

* First fork the original repo to your own github account. This process is called **Forking**.
	* Here is the url of the original repo.  https://github.com/kossiitkgp/sandbox-2018
	* First fork this.


* Now we will clone the repo to our local computer. This process is called **Cloning**.  `git clone <url>`

* `git remote -v`  : this gives the info of my remote repo
	`git remote add upstream <url>` : This will link the upstream to our local repo.

	Do `git remote -v` again. Now we can see the origin as well upstream added.

* `git branch -a` : Gives the list of branches in our repository.


* Now we will add a txt file to our repository. 

* `git status`  : We can see the result and infer from that.

* `git add .`   : Once we do git add, the changes are sent to the staging area.

https://imgur.com/FBog3NW   : Here it describes how the staging area works


* `git reset <filename>`  : Removes the file from the staging area

* `git reset` : Removes everything from the staging area as untracked file.

* `git add .`

* `git commit`

* `git diff <commit1> <commit2>`:  Gives the difference between the two commits.

* `git pull origin master` : Always do this before pushing beacuse there might be more than one contributors. This will update the local repo in case any changes have been made.

* `git push origin master` : This pushes the changes on the local computer to the origin.


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


