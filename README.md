# Learnable-Task
My Learnable task
## Learnable-Task-22-12-2024
Learnable task for the week

## Version Control

Version control is simply a system that helps track changes made to files over a period of tie. It keeps a detailed history of every change you make to a project. It helps track who made what change, when they made it, and why they made it. It also lets multiple people work on the same project at the same time without messing it up.

### Importance Of Version Control:
- **Keeps Track Of Changes**: With version control, we can see exactly what was changed, who changed it and exactly when it was changed.
- **Facilitates Colabortive Work**: There are no worries or cause for concerns about overwriting a colleague's work, as everyone's changes are tracked.
- **Branch and Merge**: We can work on different features or fixes without affecting the main project, and then merge them later.
- **Backups**: If something goes wrong, we can go back to a previous version easily.
- **Revert Mistakes**: If a change causes issues, it's easy to undo it using version control.

### Types of Version Control:
1. **Local Version Control**: Changes are stored on your computer. It’s basic but works for small projects.
2. **Centralized Version Control**: Everything’s stored on a central server in this type of verion  control. This makes it better for teams.
3. **Distributed Version Control**: Here, everyone has their own copy of the full project, like Git. This is the most popular and flexible type of version control with Git as the most common example.

In summary, version control helps us make sure we never lose work and it also makes collaboration a lot smoother, and helps tackle the problem between two or more programmers working on the same project.

# Git vs GitHub
# Differences Between Git and Github

This document explains the key differences between **Git** and **GitHub**.

## 1. Definition and Functionality

- **Git**:  
  Git is a **distributed version control system** that allows developers to track changes, collaborate on projects, and manage code. It operates locally, storing versions of files on the developer’s machine.

- **GitHub**:  
  GitHub is a **web-based platform** that hosts Git repositories. It provides a central location for version control, allowing teams to collaborate, share, and manage code online. GitHub enhances Git's capabilities with features like pull requests, issue tracking, and collaborative documentation.

## 2. Usage

- **Git**:  
  Git is used locally on your computer to manage and track changes in files. You can create branches, commit changes, and merge code without needing an online service.

- **GitHub**:  
  GitHub is used to store and share Git repositories online, enabling multiple developers to work together. It's especially useful for collaborating on large projects and sharing code with others.

## 3. Collaboration Features

- **Git**:  
  Git allows you to create repositories, branches, and commit code, but it doesn’t have built-in tools for collaboration. It focuses on version control at the individual or team level.

- **GitHub**:  
  GitHub provides rich collaboration features, such as **pull requests**, **issues**, **wikis**, and **discussions**, making it easier for teams to communicate and manage code changes across different users.

## 4. Access and Storage

- **Git**:  
  Git works completely offline, storing repositories on your local machine or a self-hosted server. You don’t need an internet connection unless pushing or pulling changes to/from a remote server.

- **GitHub**:  
  GitHub requires an internet connection and provides cloud-based storage for Git repositories. It allows easy synchronization between your local Git repository and the remote repository hosted on GitHub’s servers.

  # GITHUB ALTERNATIVES
    - Bitbucket
    - GitLab
    - SourceForge

#  Git fetch VS git pull:

git fetch:
Downloads updates (commits, branches) from a remote repository but does not merge them into your local branch. It only updates your local copy of the remote repository.

git pull:
Does the same as git fetch but automatically merges the updates into your current branch. Essentially, git pull is a combination of git fetch followed by git merge.

# Git Rebase in Simple Terms:
Git rebase moves your changes from one branch onto another, replaying your commits on top of the latest branch changes. This helps keep your history clean without creating merge commits.

How to Use:
1. git checkout feature-branch
2. git rebase main
3. git add <file>
git rebase --continue
4. git push --force

# Git Cherry-pick in Simple Terms:
Git cherry-pick allows you to apply a specific commit from one branch to another. It's like picking a commit from a tree and applying it where you need it without merging the whole branch.

How to Use:
1. Find the commit you want to apply:
Use git log to find the commit hash (the long alphanumeric string).

2. Cherry-pick the commit:
Run this command to apply the commit to your current branch:

git cherry-pick <commit-hash>
Replace <commit-hash> with the actual commit ID.

3. Handle conflicts:
If there are conflicts, resolve them, then continue:

git add <resolved-file>
git cherry-pick --continue
Cherry-pick is useful when you want to bring specific changes from one branch without bringing in everything else!

# NOTE:
Everything in angle brackets "<>" is to be edited to specification.
