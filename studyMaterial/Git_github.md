# Git and Github

## GIT - Definition

- Git its a version control system, **keeps track of changes** in your code.
- You can create diferent versions of the proyect and swap between them easily.
- This control systems let you undo changes and get back to an older version.
- It's ideal for working on Teams. Each member has his own version stored localy on their machine, this way no one overwrites other peoples work.

## GITHUB - Definition

- Is a  remote repository thats centralize all the code in one place. 
- Is a website when all the developers can store their projects and easily share and collaborate with others.


## Why GIT its importante? 

-  As GIT tracks all the changes you make at the code, you can easily search all the changes made and quickly locate the problem. 
-  GIT let you go back to a previous version of your code with a single command. 
-  87% of developers and companies use this control system, so for finding a job it's important to know it.


### Once GIT and github it's installed in our pc's we have two choices.

- Initialize: in a project that you already have in your pc.
    Open the terminal in the directory of your folder and enter the command. This adds a .git folder to you directory that will track all the changes. 
```sh
git init 
``` 
    
- Clone: when you want to take a project from github. You go to the github website, create a repository and copy the ssh_url. Then enter the command.
```sh
git clone ssh_url
``` 

## GIT Structure

GIT have three important parts
 
- Working directory
- Index
- HEAD