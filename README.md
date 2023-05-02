# Ar-git-help
The goal of this repository is to empower users with the knowledge and resources they need to effectively use git command line interfaces.
________________________________________________

## What is git 
Git is a free, open-source distributed version control system used to manage software development projects and track changes to code. 
Created by Linus Torvalds in 2005. 

Git allows multiple developers to collaborate on the same codebase, while maintaining a complete history of changes. It enables developers to work on their own copy of the code, or "branch," and then merge their changes back into the main codebase when they are ready. 

Git provides tools for tracking changes, reviewing and approving changes, and resolving conflicts. Its popularity and versatility have made it an essential tool for many teams and organizations across industries, not only for software development but also for managing content and documentation.

## Configure the git 
After installing Git on your computer, the first thing you need to do is to configure the git. For that you can follow these steps.

Note: If you want to show commits on your GitHub profile then make sure that you have entered your GitHub email.

```
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

## Creating local repo
- Go to folder where you want to create git repository
- Than open the cmd console/git console and type the following command 

```
git init 
```

- Now create the new files in the folder. 
- Make changes

## Checking the status 
To check the status of the repository type the following command 

```
git status
```

## Staging
Before commiting the changes we need to stage the files

- Staging a single file

```
git add filename.extention
```

- Staging all the files 

```
git add .
```

or 

```
git add -all
```

## Commiting
Now everything is ready to commit. You can run the following command to commit the changes. 

```
git commit -m "Your commit messages goes here"
```



