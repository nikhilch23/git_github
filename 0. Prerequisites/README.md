<!-- (## Speakers:

	* 
	*
	*
	*

## Co-ordinators:

	*
	*
	*
	*
-->
# Pre-requisites

Welcome all to this Git/ GitHub workshop.


### What are we going to learn today?

1. Basic Linux Commands
2. Introduction to Version Control
3. Track your project using git
4. Contributing to a project

### Make your GitHub account: https://www.github.com.

## Windows: 

Follow the instructions on the blog: https://blog.kossiitkgp.in/using-git-bash-for-git-in-windows-d1876774fae3 || https://bit.ly/2RtFuaZ

## Mac:

Homebrew (http://brew.sh/) is an alternative to install Git. If you have Homebrew installed, install Git via

`brew install git`

## Linux:

1. Execute `git --version` in the command line.
2. If you get a valid version number, you have git already installed on your computer, else follow the instructions below.

#### Install git

1. Execute the following command: `sudo apt-get install git`. Type your password when prompted which won't be visible to you.
2. Execute `git --version` in command line to verify installation.

#### Configure git:

1. After you've installed git properly, it's time to set some variables for the git configuration. You've to do this only once. Follow the commands on terminal.

	* `git config --global user.name "ABC"`
	* `git config --global user.email "abc.iitkgp@gmail.com"`
	* `git config --global http.proxy http://172.16.2.30:8080`      // Setting system.proxy in git
    * `git config --global core.editor gedit`

3. Now check `git config --list` to know you've set the variables correctly.


Congratulations, you've git up and running on your computer. Now, it's time to start learning git.
