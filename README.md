# Day 1

<!-- TABLE OF CONTENTS -->

## Table of Contents

In this part we learn about :

-   [Overview of GIT](#Overview-of-GIT)
-   [Important Linux Commands](#Important-Linux-Commands)
-   [Git Commands](#Git-Commands)
-   [Github Pages](#Github-Pages)
<hr>

<!-- ABOUT THE PROJECT -->

## Overview of GIT
### What is Git?
Git is free and open source software for distributed version control: tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development.

### What is GitHub?
GitHub is an Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project.

### Version control?
It is a software that tracks and manages changes to file overtime.

### Installing Git
Go to the Link below and download according to your computers specifications.<br>
```https://git-scm.com/downloads```

<strong>Keep all the default settings while installing.</strong>
<hr>

## Important Linux Commands
1. <strong>cd :-</strong> Change Directory<br>
To go into a folder<br>
```cd folder_name```<br>
To go back to a outer folder<br>
```cd ..```
2. <strong>mkdir :-</strong> Used to make a new folder/Directory.<br>
```mkdir new_folder_name```
3. <strong>touch :-</strong> Used to create a new file.<br>
```touch filename.extension```
4. <strong>pwd :-</strong> Used to print working directory<br>
```pwd```
5. <strong>ls :-</strong> Used to print contents of directory<br>
```ls```
<hr>

##  Git Commands

1. <strong> Git config –global user.name ”your_username” :- </strong> Using this command you can set or change the name that is associated with your git commits.<br>
```Git config –global user.name ”your_username”```<br>

2. <strong> Git config –global user.email ”your_email”  :- </strong> Using this command you can set or change your git identity using the git config command.<br>
```Git config –global user.email ”your_email”```<br>

3. <strong> Git init :- </strong> This command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository.<br>
```git init```<br>

4. <strong> Git add :- </strong> The git add command adds a change in the working directory to the staging area.<br>
Git add . - adds all the files to the staging area.<br>
```git add .```<br>
Git add “filename” - adds the specific files to the staging area.<br>
```Git add “filename”```<br>

5. <strong> Git status :- </strong> The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.<br>
```git status```<br>

6. <strong> Git version :- </strong> You can check your current version of Git by running the git --version command in a terminal.<br>
```git --version```<br>

7. <strong> Git commit :- </strong> The git commit command captures a snapshot of the project's currently staged changes. Committed snapshots can be thought of as “safe” versions of a project—Git will never change them unless you explicitly ask it to.<br>
```Git commit -m “your commit message”```<br>

8. <strong> Git log :- </strong> Git log is a utility tool to review and read a history of everything that happens to a repository.<br>
```git log```<br>

9. <strong> Git clone :- </strong> git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location.<br>
```Git clone \<url of repo you want to clone>```<br>

10. <strong> Git push :- </strong> The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo.<br>
```Git push \<url of repo you want to push to>```<br>
<hr>

## Github Pages

1. Clone the ISTE repo on your device. (https://github.com/ISTE-VESIT-ORG/Gitway-OpenSource)
2. Add your name to the code.
3. Use command git add . to add files to staging area.
4. Use git commit -m ”added my name” to commit the changes.
5. Create a new repo.
6. Push the code to your repo.
7. Open your repo on github.
8. Open Settings, Click on pages.
9. In the branches section select main.
10. Click on save <br> <br>
It will take a minute or two and a link will be generated. This is the link to your webpage that is hosted by github.


