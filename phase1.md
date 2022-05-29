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
ls -a # use -a to show hidden files and verify you have .git folder
```

## Create the first commit

We first create new file. 
```
echo US > countries.txt
```

The command `git status` tells us about the status of the repository. 
```
% git status
```

<img width="820" alt="image" src="https://user-images.githubusercontent.com/100768144/170857613-fbb47150-2f16-4b4e-ab44-4a3941d98643.png">

As can see, we added new file. This file was not added to the repostiory yet, so it is listed under untracked files. 
Now we need to run `git add` to add this file to the repository, so it will be part of the version control

```
git add countries.txt
```
Now if we run the git status again, we see that this was staged and it will be committed in the next commit. 
<img width="576" alt="image" src="https://user-images.githubusercontent.com/100768144/170857664-f15e675a-675a-46ae-8606-622744ef65ff.png">

So let's create the first commit. When committing, we need to provide commit message. We can write `git commit` and then we will be prompted to commit message, or we can pass the comment as parameter `git commit -m "comment"`. So let's commit.
```
git commit -m "added countries file"
```
If we run git status again, we see that there is nothing to commit.

<img width="426" alt="image" src="https://user-images.githubusercontent.com/100768144/170857904-1f9391b1-9e90-459f-8669-3b1c187e5d76.png">


**Congrats! You just created your first commit**


