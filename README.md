<div align="center">

# Git Tutorial for OSC

<img src="https://s24255.pcdn.co/wp-content/uploads/2015/02/Git.png" height="250px" width="250px">

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

## Important Linux Command

here is some helpfull commands in this tutorial

```
pwd : to show the current path
mkdir < chooseAnyName > : to creat a new directory in current path
cd < dirName > : to change path to the chosen directory
rm -rf < dirOrFileName > : to delete file or directory in the current path
touch < chosseAnyName > : to create a new file tn current path
```

### Step #1: Installing Git

Download git from the official website [Git](https://git-scm.com/). 

Make sure to have this option, but other than that everything is default.

<img src="pictures/gitbashsure.png">

### Step #2: Create directory for tutorial
```
mkdir git-tutorial
cd git-tutorial
```

<img src="pictures/step2.png">


### Step #3: Initialize git repository
```
git init
```

<img src="pictures/step3.png">


### Step #4: Check status of empty git repository
```
git status
```

<img src="pictures/step4.png">

### Step #5: Create empty file
```
touch file.txt
ls
```

<img src="pictures/step5.png">


### Step #6: Check status of repository when a file is added
```
git status
```

<img src="pictures/step6.png">

### Step #7: Add file to staging
```
git add file.txt
```

<img src="pictures/step7.png">


### Step #8: Configure email and user name
```
git config --global user.email "YourEmail@gmail.com"
git config --global user.name "Your Name"
```

<img src="pictures/step8.png">

### Step #9 Make a commit
```
git commit -m "my first commit!"
```

<img src="pictures/step9.png">


### Step #10: Check git log
```
git log
```

<img src="pictures/step10.png">

### Step #11: Make github account and repository

Create an account on Github
<img src="pictures/step11.png">

Then create a repository by clicking on the top right "+" then "new repository".

<img src="pictures/step11-1.png">

After that give it a name 

<img src="pictures/step11-2.png">

### Step #12: Add remote url to local git repository
```
git remote add origin <link to repo>
```

first we have to copy the url of the repository we just made on github

<img src="pictures/step12.png">

then we do the above command

<img src="pictures/step12-1.png">

### Step #13: Push local repository to remote repository

```
git push -u <remote repo> <branch name>
```

Here it will ask you for your github username and password

<img src="pictures/step13.png">



## And thats it! 

<img src="pictures/done.png">
