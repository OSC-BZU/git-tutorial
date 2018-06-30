<div align="center">

# Git Tutorial for OSC

<img src="https://avatars0.githubusercontent.com/u/4571183?s=200&v=4" height="250px" width="250px">

##### A small tutorial for git that was prepared for an event for OSC - BZU

</div>

## Goals of this tutorial

1. Understand the basics of *git*
2. Create a local git repository using the command line
3. *Push* local git repository to github


## Important Git Commands
```
git init
git status
git add <file name> 
git commit -m "your message"
git push -u <remote name> <branch name>
```



### Step #1: Installing Git

Download git from the official website [Git](https://git-scm.com/). 



### Step #2: Create directory for tutorial
```
mkdir git-tutorial
cd git-tutorial
```

<img src="step2.png">


### Step #3: Initialize git repository
```
git init
```

<img src="step3.png">


### Step #4: Check status of empty git repository
```
git status
```

<img src="step4.png">

### Step #5: Create empty file
```
touch file.txt
ls
```

<img src="step5.png">


### Step #6: Check status of repository when a file is added
```
git status
```

<img src="step6.png">

### Step #7: Add file to staging
```
git add file.txt
```

<img src="step7.png">