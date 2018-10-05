Points to cover:


1. Introduce to github.
2. Tell concepts of remote(origin and upstream)
3. First teach to fork and then clone. A proper diagram has to be represented about the work flow. 
4. here teach git pull, git fetch, git push as well to the local repo. 
5. Teach how to push to your local repo. Introduce PR here. We will have to discuss how we can structure this page well.

6. I want the people to learn two ways. 
a) Make their own repo and push it to the origin. (git add origin <url> has to be used here.)
b) Clone a repo and contribute there.





1. 

* git clone <url>

* git remote -v  : this gives the info of my remote repo

* git branch -a

* git diff

* git add
* git commit

* git pull origin master : Always do this before pushing beacuse there might be more than one contributors. This will update 
* git push origin master


* Git add . 

* git commit
* git reset calc.py  : Removes the file from the staging area
* git reset : Removes everything from the staging area as untracked file.


* git commit -m ".....message"


* git log : Gives the commits list



### Common workflow

* git branch xyz
* git branch: astrisk beside the branch name implies the current branch
* git checkout xyz

* git push origin xyz : We have pushed xyz branch to the remote.

* git checkout master.
* git pulll origin master
* git branch --merged : Says which branches have been merged till now.
* git merge xyz
* git push origin master