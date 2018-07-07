

<div align="center">

# Git Tutorial for OSC in Arabic

<img src="https://s24255.pcdn.co/wp-content/uploads/2015/02/Git.png" height="250px" width="250px"> 

####������ ������ ���� � git  �� ������ ���� � OSC � BZU

</div>

##����� �������� 

1.��� ������� Git .
2.����� local git repository �� ������ command line  .
3.����� local git repository ��� ���� github .

##������� ������ �� Git 
```
git init
git status
git add <file name> 
git commit -m "your message"
git push -u <remote name> <branch name>
```

##������ ������ : ����� Git 

�� ������ [Git](https://git-scm.com/) �� ������ ������ .

���� �� ����� ��� ��� �������� , ��� �� ��� ��� ��� ���� ������� . 

<img src="pictures/gitbashsure.png">

##������ ������� : ����� ���� � �������� 
```
mkdir git-tutorial
cd git-tutorial
```

<img src="pictures/step2.png">

##������ ������� : ����� git repository 
```
git init
```

<img src="pictures/step3.png">




##������ ������� : ������ �� git repository ��� ���� ����� 
```
git status
```

<img src="pictures/step4.png">

##������ ������� : ����� ��� ���� 

```
touch file.txt
ls
```

<img src="pictures/step5.png">


##������ ������� : ������ �� ���� repository ��� ����� ����� 

```
git status
```

<img src="pictures/step6.png">

������ : ��� ���� ��� ����� ^ ^

##������ ������� : ����� ����� ��� ������ 

```
git add file.txt
```

<img src="pictures/step7.png">

##������ ������� : ����� ������� � ����� 

```
git config --global user.email "YourEmail@gmail.com"
git config --global user.name "Your Name"
```

<img src="pictures/step8.png">

##������ ������� : �����  a commit 

```
git commit -m "my first commit!"
```

<img src="pictures/step9.png">




##������ ������� : ������ �� ���  Git 

```
git log
```

<img src="pictures/step10.png">

##������ ������� ��� : ����� ���� � repository ��� github 

����� ���� ��� github 

<img src="pictures/step11.png">

��� ��� �� ������ repository ������ ��� ���� ������ "+" �� "new repository" . 

<img src="pictures/step11-1.png">

��� ��� �� ���� ��� �� .

<img src="pictures/step11-2.png">

##������ ������� ��� : ����� ������ �� ��� � local git repository 

```
git remote add origin <link to repo>
```
���� ��� ��� ������ �� repository ���� �� ������� �� github 

<img src="pictures/step12.png">

�� ���� ������ ����� 

<img src="pictures/step12-1.png"> 

##������ ������� � ����� : ��� local repository �    remot repository

```
git push -u <remote repo> <branch name>
```
��� ��� ��� ���� github ����� �� ��� �������� � ���� ������ , �� �������� . 

<img src="pictures/step13.png"> 

# � ��� �� ^ ^ 

<img src="pictures/done.png">

