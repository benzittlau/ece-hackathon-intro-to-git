## INTRODUCTION TO GIT AND GITHUB
#### http://getjobber.com
#### @benzittlau
#### http://benzittlau.com
#### http://springlaunched.com
#### http://zittlau.ca
#### http://github.com/benzittlau



## What we're going to cover
What is Git?

Why would I use it?

Installing Git

First steps in Git

Setting up a GitHub account

Creating a GitHub project

Using Git Branches and GitHub



## WHAT IS GIT?
[Version/Source Control Management](https://en.wikipedia.org/wiki/Version_control)

Keeps a versioned history of all changes (additions, removals, modifications) of all files in a project



## WHY WOULD WE USE GIT?
If you've ever named a file `index-version2.html` or `index-original.html` you've needed Git

Facilitates temporary "forks" or experiments without losing your "good" version

Powerful collaboration tool allowing multiple developers to work in the same area of code



## INSTALLING GIT
Git can be used through the command-line or through a GUI tool

I *strongly* recommend learning the command-line tool, but for today we'll start with the GUI interface

[GitHub GUI For OS X](https://mac.github.com/)

[GitHub GUI For Windows](https://mac.github.com/)


## INSTALLING GIT ON Linux
GitHub doesn't have a GUI client for Linux, so we'll use the command-line tool

```sh
$ sudo apt-get update
$ sudo apt-get install git
```


## CONFIGURING GIT(GUI)
Skip Setup when Prompted

Go to GitHub Desktop => Preferences => Advanced

Enter your name and e-mail

![Configure username and name](img/username_and_name.jpg)


## CONFIGURING GIT(CLI)
``` sh
$ git config --global user.name "YOUR NAME"
$ git config --global user.email "YOUR EMAIL ADDRESS"
```



## First steps in Git
Create a new "Repo"

Write a basic readme file

Commit the readme to the project


## Creating a new "Repo"
A repository (or Repo) is a project in Git that lives in one directory (and as many sub-directories as you want).

![Create a new repo](img/create_repo.jpg)

### In CLI
```sh
$ mkdir -p ~/GitHub/my-new-repo
$ cd ~/GitHub/my-new-repo
$ git init
```



# Resources
* [Set up Git (GitHub)](https://help.github.com/articles/set-up-git/)
* [How to write a Git commit message](http://chris.beams.io/posts/git-commit/)
* [Git From The Inside Out](https://codewords.recurse.com/issues/two/git-from-the-inside-out)

