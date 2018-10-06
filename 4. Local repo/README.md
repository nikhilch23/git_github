Mention gitignore


## Making your own project and pushing it to GitHub.

* `mkdir project`

* `cd project`

* `git init`  : This will initialise git to your folder.

* Do some edits. Commit your changes.

* Make a new branch.

* Make your changes there.

### Why should we code on a side branch rather than master? 

* Shift to master using `git checkout master` and see the changes are not seen.

* `git merge <branch name>` : This will merge the other branch to master. a very useful tool.

* `git log`

* `git diff`

Try all the commands here.

* `git push origin master` 


### Untrack a file in git?

There will be two cases:

1. You are making a new repo and have not yet committed any file in git. Make a .gitignore file in your repo and add all those file names which need to be ignored by git tracking. Then commit your changes and hence your job is done.


2. You have already committed your changes into your github repo. Now you notice that few of your files in your github repo are not of your use and you want to ignore them.
	* First you got to untrack your file.

	* `git rm -r --cached <file>`
	
	Add your files with `git add .`

	Now commit the changes using `git commit -m "gitignore fix"`

	Then push your changes to github repo `git push origin master`


## What's next?

* Start contributing.
* Take part in open source competitions like Google Summer of Code (GSoC), KWoC (Kharagpur Winter of Code), Outreachy, Rails Girls Summer of Code.
* Hactober Fest


# Code, learn, contribute, Teach.


Thank You!