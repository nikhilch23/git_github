Points to cover:

1. Install git. tell the commands.
2. Set system proxy for them in git.
3. if someone isnt yet able to connect, you might have to set system proxy on the sysytem as well. Be prepared for that.


4.  Windows:    ......


1. windows.. gitbash 
2. gitbash config
3. git configGithub Account





### Install git


## Windows: 

  Go to this webpage :   http://www.git-scm.com

0. I hope all have made their github accounts by now.

1. After the git is installed: Check this command `git --version`

2. Write the following commands on terminal.

	`git config --global user.name "Nikhil"`
	`git config --global user.email "nik.ch.23@gmail.com"`


	`git config --global http.proxy http://172.16.2.30:8080`      // Setting system.proxy in git

3. Now check `git config --list`