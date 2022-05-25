# Git Workshop - Basics

In this step, we will play with the basic git commands. We will start with an empty repository,
add files, stage and commit them.

Good luck

## Create empty repp

We will start with empty folder

* Create a new folder, cd to this folder 

```bash
mkdir my-project
cd my-project
ls  # verify empty folder
```

* Initialize the repo

To initialize the repo, we use the command git init. It will create a `.git` folder under the current folder. 
This folder used to hold all the data about the repository: commits, commits tree, current commit and more.

```
git init
ls -a. # use -a to show hidden files and verify you have .git folder
```

## Create the first commit

Since the repository is empty, to create an empty repo
