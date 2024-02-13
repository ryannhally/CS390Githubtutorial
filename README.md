# Welcome!
Welcome to my Git from the command line tutorial!

Git is a **version control system** for developers. In other words, Git allows you to manage changes to code. Once you master Git, you will be able to use it to track changes to your code and collaborate more easily with other developers, among other things.

In this tutorial will cover the basics of using Git from the command line. You will learn how to...
* Create a repository
* Add files to the repository
* Commit changes
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

## Creating a repostiory
First, we will create a **local** repository. 

Git can be used to manage both **local** and **remote** repositories. **Local** repositories live on your computer while **remote** repositories are kept on a server. If you'd like to collaborate with others on your code, or just want to be able to access your code if, for example, your computer breaks, it's important to be able to use remote repositories. In this tutorial, we will start by creating a local repository and then we will **push** (more on what that is later) it onto Github, so it is stored remotely as well. 

### Create a local repository
Move to the folder you'd like your project to be stored in and run
```
git innit
```
You've created a local respository!

### Push your repository onto Github
Now we will push our local repository onto Github. Run:
```
git remote add origin https://github.com/USERNAME/PROJECTNAME.git
```


## Adding files to your repository
### Create a file
Before you create a file, make sure you have moved into the folder you want the file stored in. Then create the file with the touch command

```
touch FILENAME.text
```

### Add the file to the staging enviornment
Just because you've created a file does not mean Git is tracking changes to the file! You must add the file to the **staging enviornment** or **index**. This is where Git tracks what will go into your next **commit** (next up).
Run:

```
git add <FILENAME>
```
Now the file is in our staging enviornment. 

## Commiting changes
Now that we've created a file and Git is tracking the changes we make to it, we can start to **commit**. Making a **commit** is like saving changes on a word document. You are saving the current state of the code. Every **commit** has a **commit message**, which you can use to add a brief description of the changes you've made. Here is how to commit:

```
git commit -m "COMMIT MESSAGE"
```

## Branching

### Create a branch
Say you way to focus in on changing a specific component of your code, like a feature. You might want to create a **branch** so you can work on it without affecting the rest of your code, and then combine it with the rest of your project once its finished. In summary, a **branch** is just a seperate version of the repository you can later combine with the main one. Create a branch with

```
git branch BRANCH NAME
```
You've created a branch!

### Switch to a branch
Just because you've created a branch doesn't mean you are working on that branch, ie, your changes are being commited to it and not the main branch. You will have to checkout the branch by running:

```
```

To both create a branch and check it out at the same time, use:

```
git checkout -b <my branch>
```

## Stashing
What if you want to save some changes you've made, but aren't quite ready to commit them? The answer to this is **stashing**.



## Merge
