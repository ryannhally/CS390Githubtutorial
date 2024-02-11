# Welcome!
Welcome to my Git from the command line tutorial!

Git is a **version control system** for developers. In other words, Git allows you to manage changes to code. Once you master Git, you will be able to use it to track changes to your code and collaborate more easily with other developers, among other things.

In this tutorial will cover the basics of using Git from the command line. You will learn how to...
* Create a repository
* Commit
* Branch
* Merge

## Getting Started

1. Open a command line

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; To work with Git from the command line, you will first need to open up your terminal of choice.
  
2. Install Git <br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; You can check to see if Git is already installed by running
   ```
   git --version
   ```
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If you don't already have Git installed, click [here](https://docs.gitlab.com/ee/topics/git/how_to_install_git/index.html) for a tutorial on how to install.
 
3. Authenticate with Github CLI

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; To easily manage your credentials, download Github CLI [here](https://github.com/cli/cli#installation). Next, run
```
gh auth login
```
Follow the prompts.

## Create a repostiory
First, we will create a local repository on the command line. 

### Some background...

There are both **local** and **remote** repositories. **Local** repositories live on your computer while **remote** repositories are kept on a server. If you'd like to collaborate with others on your code, or just want to be able to access your code if, for example, your computer breaks, it's important to be able to use remote repositories. In this tutorial, we will start by creating a local repository and then **pushing** (more on what that is later) onto Github, so it is stored in a remote repository. 

### Create a local repository
Move into whereever you'd like your project to be stored and run
```
git innit
```
You've now created a local respository!

### Push your repository onto Github
Run
```
git remote add origin https://github.com/USERNAME/PROJECTNAME.git
```
Now you've pushed in onto github!

## Create a file


## Commit 

## Branch

## Stash

## Merge
