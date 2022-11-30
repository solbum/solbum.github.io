---
layout:	post
title:	"Git & Github"
date:	2022-11-30 20:52:37 +0900
categories: gitGithub update
---

![GitImage](https://images.velog.io/images/leobit/post/76a66545-6226-411b-9346-61ba0e9531cc/git.png)

## What if Git?
<dt>Version Control</dt>
<dd>Git is a version management system for conveniently and specifically recording when and what changes were made whenever a document was modified.</dd>

<dt>Backup</dt>
<dd>Backup is to replicate data that is currently on a computer to another computer</dd>

<dt>Collaboration</dt>
<dd>Using online services such as GitHub, team members can comfortably exchange and work with GitHub.</dd>

***
***

## Git Program

* [GitHub Desktop](https://desktop.github.com/)
* [TortoiseGit](https://tortoisegit.org/)
* [SourceTree](https://www.sourcetreeapp.com/)

Git Program makes it more convenient to use the Git, also known as the Git Client Program.

***
***

## Command Line Interface, CLI

Command Line Interface is a method of using Git by entering a command directly into a terminal window

***
***

## How to use Git
![gitInit](/git_init.png)
>Specifies the current directory as a git repository.


![gitStatus](/git_status.png)
>Check current Git status


![gitAdd](/git_add.png)
>If you want to create (or modify) example.py and reflect it in your Commit


![gitLog](/git_log.png)
>Check Commit history


***
***

## Branch of Git

<dt>Why we need branch in Git?</dt>
![gitBranch](/git_brunch.png)
<dd>Distributing the flow of code enables more efficient development</dd>

***

### The use of Branch of Git

* Create a branch with 

```git
git branch <branch name>
```

* Switch the branch

```git
git checkout <branch_name>
```

* Merge the branch you are currently working on into the desired branch.

```git
 git merge <branch_name>
```

[Back](./)
