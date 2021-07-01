# Git and Github

## This repository
> In this course we learn the git main commands and how to implement them in our projects, also we study the necessary concepts to understand how it works internally.

## Overview
####  What is git?
> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

####  What is github?
> GitHub is one of the world’s largest community of developers. It’s an intricate platform that fosters collaboration and communication between developers. GitHub has a number of useful features that enable development teams to work together on the same project and easily create new versions of software without disrupting the current versions.

## Dependencies

> - Install [Git](https://git-scm.com/downloads) 
> - Install [VisualStudioCode](https://code.visualstudio.com/download)

## Commands and Concepts
> Any Git project will consist of three sections: 
> - The Git directory 
> - The Working tree
> - The Staging area.

#### Git directory
> - The Git directory is where Git stores the metadata and object database for your project. This is the most important part of Git, and it is what is copied when you clone a repository from another computer.

#### The working tree
> - The working tree, or working directory, consists of files that you are currently working on. You can think of a working tree as a file system where you can view and modify files.

#### The Staging area
> - The staging area is like a rough draft space, it's where you can git add the version of a file or multiple files that you want to save in your next commit, in other words in the next version of your project.

![image](https://user-images.githubusercontent.com/79294934/124152061-cd396500-da58-11eb-9db8-b1ff09918505.png)


## Git basic commands
> - `git init [repository name]`: This command is used to start a new repository.
> - `git clone [url]`: This command is used to obtain a repository from an existing URL.
> - `git add [file]`: This command adds a file to the staging area.
> - `git commit -m “[ Type in the commit message]”`: This command records or snapshots the file permanently in the version history.
> - `git commit -a`: This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.
> - `git status`: This command lists all the files that have to be committed.
> - `git log`: This command is used to list the version history for the current branch.
> - `git push [variable name] [branch]`: This command sends the committed changes of master branch to your remote repository.
> - `git pull [Repository Link]`: This command fetches and merges changes on the remote server to your working directory.
> 

## More information 
> - [Command examples](https://dzone.com/articles/top-20-git-commands-with-examples)
> - [Git - What is Git?](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F)
> - [What is the use of the staging area in git?](https://stackoverflow.com/questions/49228209/whats-the-use-of-the-staging-area-in-git)

## Documents

 > - blogspot.html
 > - historia.txt
 > - estilos.css
 
 ## Run Code
 > Clone this repository into a new directory
 > ```
 > git clone https://github.com/NaraPG/hyperblog.git
 > ```
 > Open it in your code editor
 > ```
 > code .
 > ```
 > Go to `blogpost.html` and press `Shift + Alt + R` to reveal in file explorer

 
>  


_Created by Nara Peña Gámez_
