## Version Control

#### -This allows one to go back to earlier versions of a file to see the full record of changes. You can even revert back to an eariler file if you wish.

#### -Centralized Version Control has a single server storing all file versions, including all changes. This allows those collaborating on a project to understand changes made by others in real time.

#### -Distributed Version Contol systems solve the issue of having a single server, which is suseptible to failure. This makes 'mirrored repositories', which allow for the sum total work on a file to be saved even if one or multiple servers or computers go down. 

## What is Git?

#### It's a DVCS that stores snapshots of a file in a file system. For every commit, Git makes a snapshot so you can reference it again. 

#### Git relies on local operations for expediency's sake. It also traks changes so you can prevent the loss of data or your place during building/editing files. Git also exists in several states, including committed, modified, and staged.

## [Here's a link for Git download instructions](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## Post-Installation Customization

#### You need to ensure you configure your variables using "git config" to ensure your optimal settings and look.

#### You next need to setup your identity by typing "git config --global user.name "Your Name" and git config --global user.email "Your Email"

#### If you need help during this process, type "git help command"

## Setting up Git Repository

#### Switch to the target project’s directory
###### Example:
###### $ cd test (cd = change directory)
###### Use the git init command
###### $ git init

###### To start tracking these repository files, perform an initial commit by typing the following:
###### $ git add *.c
###### $ git add LICENSE
###### $ git commit -m “any message here”

## Cloning Repos

#### You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

###### $ git clone https://github.com/test

## Workflow

#### Local Repo Structure is Working Directory (actual files are here), Index (area used for staging), and Head (point of most recent commit)

#### Check file status by tying "git status"

#### track files by single "git add filename" or all "git add *"

#### commit a file by typing "git commit -m 'text describing changes made'

#### commit all changes by typing "git commit -a"

#### push changes by writing "git push origin master"

