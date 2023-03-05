# Git - Github study

<p><i>Just a summary of the most important commands and concepts of Git and Github. My development environment is Windows 11, but after installing Git Bash on a Windows computer, users have the same set of Git commands available as in Git's native environment (a Unix-style system like Linux or macOS).</i></p>

# Table of Contents

### 1. [Git](#I-git)

-  [Git - Github study](#git---github-study)
-  [Table of Contents](#table-of-contents)
   -  [1. Git](#1-git)
   -  [2. GitHub](#2-github)
-  [I. Git](#i-git)
   -  [I.1. What is Git?](#i1-what-is-git)
   -  [I.2. Git Installation and Configuration](#i2-git-installation-and-configuration)
      -  [I.2.1. Install Git](#i21-install-git)
      -  [I.2.2. Configure Git](#i22-configure-git)
   -  [I.3. Git terms](#i3-git-terms)
      -  [I.3.1. Repository](#i31-repository)
      -  [I.3.2. Working directory](#i32-working-directory)
      -  [I.3.3. Staging area](#i33-staging-area)
      -  [I.3.4. Commit](#i34-commit)
      -  [I.3.5. Branch](#i35-branch)
      -  [I.3.6. Merge](#i36-merge)
      -  [I.3.8. Fork](#i38-fork)
      -  [I.3.9. Pull request](#i39-pull-request)
      -  [I.3.10. Clone](#i310-clone)
      -  [I.3.11. Push](#i311-push)
      -  [I.3.12. Pull](#i312-pull)
      -  [I.3.13. Fetch](#i313-fetch)
      -  [I.3.14. Remote](#i314-remote)
      -  [I.3.15. Origin](#i315-origin)
      -  [I.3.16. Upstream](#i316-upstream)
      -  [I.3.17. HEAD](#i317-head)
      -  [I.3.18. Master](#i318-master)
      -  [I.3.19. Stash](#i319-stash)
      -  [I.3.20. Tag](#i320-tag)
      -  [I.3.21. Revert](#i321-revert)
      -  [I.3.22. Reset](#i322-reset)
      -  [I.3.23. Checkout](#i323-checkout)
      -  [I.3.24. Diff](#i324-diff)
      -  [I.3.25. Status](#i325-status)
      -  [I.3.26. Log](#i326-log)
   -  [I.4. Git basic command](#i4-git-basic-command)
      -  [I.4.1. git status](#i41-git-status)
      -  [I.4.2. git init](#i42-git-init)
      -  [I.4.3. git add](#i43-git-add)
      -  [I.4.4. git commit](#i44-git-commit)
      -  [I.4.5. git log](#i45-git-log)
      -  [I.4.6. git branch](#i46-git-branch)
      -  [I.4.7. git checkout](#i47-git-checkout)
      -  [I.4.8. git merge](#i48-git-merge)
      -  [I.4.9. git diff](#i49-git-diff)
      -  [I.4.10. git stash](#i410-git-stash)
      -  [I.4.11. git tag](#i411-git-tag)
      -  [I.4.12. git revert](#i412-git-revert)
      -  [I.4.13. git reset](#i413-git-reset)
      -  [I.4.14. git remote](#i414-git-remote)
      -  [I.4.15. git push](#i415-git-push)
      -  [I.4.16. git pull](#i416-git-pull)
      -  [I.4.17. git fetch](#i417-git-fetch)
      -  [I.4.18. git clone](#i418-git-clone)
      -  [I.4.19. git config](#i419-git-config)
      -  [I.4.20. git mv](#i420-git-mv)
      -  [I.4.21. git rm](#i421-git-rm)
      -  [I.4.22. git restore](#i422-git-restore)
-  [II. GitHub](#ii-github)

### 2. [GitHub](#II-github)

---

# I. Git

## I.1. What is Git?

Simplify, Git is a tool that helps developers keep track of changes made to their code. It allows multiple people to work on the same codebase without causing conflicts. It also helps developers undo changes or experiment with new features without affecting the main codebase. Git is widely used in software development because it is flexible, fast, and reliable. There are also many tools and services available that integrate with Git, making it easy to use in various development workflows.

You can think of Git as a time machine that allows you to travel back to previous versions of your code. It also allows you to travel to different timelines, where you can create new versions of your code without affecting the main timeline. This is useful when you want to experiment with new features without affecting the main codebase.

About history of Git, you can check it by yourself [here](https://www.geeksforgeeks.org/history-of-git/).

## I.2. Git Installation and Configuration

### I.2.1. Install Git

You can download Git [here](https://git-scm.com/downloads). After downloading, you can install Git by following the instructions on the screen.

### I.2.2. Configure Git

Config Git is very important. It will help you to identify who you are when you commit changes to the repository. Just open your terminal and type:

```bash
git config --global user.name [your_username]
git config --global user.email [your_email]
```

Example:

```bash
git config --global user.name "Mr Brown"
git config --global user.email browninsuit@gmail.com
```

## I.3. Git terms

### I.3.1. Repository

### I.3.2. Working directory

### I.3.3. Staging area

### I.3.4. Commit

### I.3.5. Branch

### I.3.6. Merge

### I.3.8. Fork

### I.3.9. Pull request

### I.3.10. Clone

### I.3.11. Push

### I.3.12. Pull

### I.3.13. Fetch

### I.3.14. Remote

### I.3.15. Origin

### I.3.16. Upstream

### I.3.17. HEAD

### I.3.18. Master

### I.3.19. Stash

### I.3.20. Tag

### I.3.21. Revert

### I.3.22. Reset

### I.3.23. Checkout

### I.3.24. Diff

### I.3.25. Status

### I.3.26. Log

## I.4. Git basic command

### I.4.1. git status

### I.4.2. git init

### I.4.3. git add

### I.4.4. git commit

### I.4.5. git log

### I.4.6. git branch

### I.4.7. git checkout

### I.4.8. git merge

### I.4.9. git diff

### I.4.10. git stash

### I.4.11. git tag

### I.4.12. git revert

### I.4.13. git reset

### I.4.14. git remote

### I.4.15. git push

### I.4.16. git pull

### I.4.17. git fetch

### I.4.18. git clone

### I.4.19. git config

### I.4.20. git mv

### I.4.21. git rm

### I.4.22. git restore

---

# II. GitHub
