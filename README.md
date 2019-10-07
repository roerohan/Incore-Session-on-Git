# Introductory Session on Git and GitHub

Incore session on Git and GitHub.

## Table of Contents
- [Requirements](#requirements)
- [Why Git or GitHub?](#why-git-or-github)
- [Using Git](#using-git)
- [GitHub](#github)
- [CodeHub](#codehub)

## Requirements
1. [git](https://git-scm.com/downloads)
2. [GitHub Account] (https://education.github.com/pack)
3. A Text Editor - [VSCode](https://code.visualstudio.com/download)

## Why Git or GitHub?
- What is Git?
- What is GitHub?
- Importance
- What is a remote repository?
- What is a local repository?

## Using Git
- Basic Commands:
    * git init
    * git add
    * git commit
    * git push
    * git pull
    * git status

```
Live Demo
- Create a Repository
- Add collaborators (groups of 2)
- Clone the repository
- Open the repository on VSCode
- Make changes to the repository (target.md).
- Pull the changes made by others.
- Push to remote repository
```

- Other Useful Commands:
    * git branch (concept, **Forks**)
    * git checkout
    * git remote (concept)
    * git merge
    * git reset
    * git diff

```
Live Demo
- Merge conflict demonstration
- Fork main repository
- Clone the Forked repository
- Create a branch and checkout to that branch
- Push the branch (--set-upstream)
- Checkout to master and merge the new branch
- Push to master
- Add remote to main repository
- Pull from main repository
- Make Pull Requests
```

- Setup:
    * Personal Information: git config
    * Ignore: .gitignore

## GitHub

- What's .md (Markdown)?
- Pull Requests
- Issues
- Community Convention:

> [Check this](https://github.com/roerohan/vscode-MongoSnippets-NodeJS) for reference

    * Description (and Tags)
    * README
    * CONTRIBUTING
    * PULL REQUEST TEMPLATES
    * ISSUE TEMPLATES
    * CODE OF CONDUCT
    * LICENSE

## CodeHub

Most frequently used commands:

```bash
Structure: git <operation> <options> <parameters>
Help: git --help

git init
git add . OR git add <file/folder-names>
git commit -m "message"
git pull
git push

git branch <branch-name>
git checkout <branch-name>
git merge <branch-name>
git branch -d <branch-name>
git branch -D <branch-name>

git diff
git log
git status
git fetch

git remote add <remote-name> <url>
git remote rm <remote-name>

git stash
git stash clear

git reset HEAD
git reset HEAD^
git reset --hard
```
