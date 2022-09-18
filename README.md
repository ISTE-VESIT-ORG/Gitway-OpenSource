# Day 2

In this part we learn about :

-   [Branching](#what-is-git-branching)
-   [Merging](#merging-branches)
-   [Merge conflict](#what-is-a-git-merge-conflict)
-   [Open source](#what-do-you-mean-by-open-source-contribution)
-   [Forking](#what-is-a-fork)
-   [Profile Readme](#what-is-a-github-profile-readme)

<hr>

## What is Git Branching?

Git branching allows developers to diverge from the production version of code to fix a bug or add a feature. Developers create branches to work with a copy of the code without modifying the existing version. You create branches to isolate your code changes, which you test before merging to the main branch

![image](https://res.cloudinary.com/sarveshp46/image/upload/v1663178481/git-workshop-readme/branching_ono19c.webp)
<br/><br/>

### How to Create a Branch in Git

Enough theory, let’s create some branches! These examples will be using PowerShell 7 on a Windows 10 system; however, you can use any terminal that supports Git commands.<br/><br/>

#### Option 1: Creating a Branch

To create a branch, use the git branch command followed by the name of the branch. After making the branch, use git branch again to view available branches.

Notice that creating a branch this way does not automatically switch to the new branch. Git uses an asterisk and a different colored font to identify which branch is active. This designation represents the HEAD pointer showing which branch is active.

```
git branch <branch name>

git branch
```

#### Option 2: Creating a Branch using Checkout

If you want to create a branch and checkout the branch simultaneously, use the git checkoutcommand. The switch -b specifies the name of the branch. Note that after command completion, Git has moved HEAD to the new branch.

```
git checkout -b <branch name>

git branch
```

<hr>
<br/>

## Merging Branches

Once you’ve completed work on your branch, it is time to merge it into the main branch. Merging takes your branch changes and implements them into the main branch.
<br/><br/>

### Merging Branches in a Local Repository

To merge branches locally, use git checkoutto switch to the branch you want to merge into. This branch is typically the main branch. Next, use git mergeand specify the name of the other branch to bring into this branch. This example merges the sarvesh/feature1 branch into the main branch. Note that this is a fast-forward merge.

```
git checkout main

git merge sarvesh/feature1
```

<br/>

### Merging on github

-   Click on pull requests tab on the github repository homepage
    ![image](https://res.cloudinary.com/sarveshp46/image/upload/v1663178482/git-workshop-readme/merge1_n5xyln.png)
-   Click on new pull request button to create a new pull request for merging the two branches
    ![image](https://res.cloudinary.com/sarveshp46/image/upload/v1663178482/git-workshop-readme/merge2_deydmq.png)
-   Just add a comment and then click on create pull request button
    ![image](https://res.cloudinary.com/sarveshp46/image/upload/v1663178482/git-workshop-readme/merge3_znidmb.png)
-   Thus the pull request has been created successfully and you can merge by simply clicking on merge pull request button
![image](https://res.cloudinary.com/sarveshp46/image/upload/v1663178482/git-workshop-readme/merge4_jcu0mf.png)
<hr>

## What is a Git Merge Conflict?

A merge conflict is an event that takes place when Git is unable to automatically resolve differences in code between two commits. Git can merge the changes automatically only if the commits are on different lines or branches.
The following is an example of how a Git merge conflict works:
<br/><br/>

![image](https://res.cloudinary.com/sarveshp46/image/upload/v1663178481/git-workshop-readme/merge-conflicts_u26vj4.jpg)

<br/>
Let’s assume there are two developers: Developer A and Developer B. Both of them pull the same code file from the remote repository and try to make various amendments in that file. After making the changes, Developer A pushes the file back to the remote repository from his local repository. Now, when Developer B tries to push that file after making the changes from his end, he is unable to do so, as the file has already been changed in the remote repository.<br/><br/>

<hr>

## What do you mean by open-source contribution?

Open-Source Software is a type of software whose code is publicly available to use and modify. Open-Source Contribution involves contributing to the development or improvement of open-source software.

Some popular Open-Source Software are the Linux Operating System, Android, Mozilla Firefox, Chromium (which powers Google Chrome and Microsoft Edge), VSCode IDE, VLC Media Player, WordPress Content Manager System, etc.<br/><br/>

### What is a fork?

A GitHub fork is a copy of a repository (repo) that sits in your account rather than the account from which you forked the data from. Once you have forked a repo, you own your forked copy. This means that you can edit the contents of your forked repository without impacting the parent repo.

### How to Fork a Repo

You can fork any repo by clicking the fork button in the upper right hand corner of a repo page.
![image](https://res.cloudinary.com/sarveshp46/image/upload/v1663178481/git-workshop-readme/fork_r8eniz.png)
<br/><br/>

<hr>

## What is a GitHub Profile README?

A GitHub profile README is a feature of GitHub that allows users to use a Markdown file named README to write details about themselves such as their skills, interests, GitHub stats and showcase it to the GitHub community. It’s shown at the top of your GitHub home page, above the pinned repositories. This is a fancy way to showcase one’s skills and stats on GitHub. Following is an example of a GitHub profile README:

![image](https://res.cloudinary.com/sarveshp46/image/upload/v1663178483/git-workshop-readme/profile-readme_lsp5od.png)
