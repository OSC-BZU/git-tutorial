

<div align="center">

# Git Tutorial for OSC in Arabic

<img src="https://s24255.pcdn.co/wp-content/uploads/2015/02/Git.png" height="250px" width="250px"> 
<div  dir=�rtl�  align=�right�> 
####������ ������ ���� � git  �� ������ ���� � OSC � BZU
</div>
</div>
<div  dir="rtl"  align="right"> 

### ����� �������� 
</div>
<div  dir="rtl"  align="right"> 

1.��� ������� Git .

2.����� local git repository �� ������ command line  .

3.����� local git repository ��� ���� github .

</div>
<div  dir="rtl"  align="right"> 

### ������� ������ �� Git 

</div>
```
git init
git status
git add <file name> 
git commit -m "your message"
git push -u <remote name> <branch name>
```
<div  dir="rtl"  align="right">

### ������ ������ : ����� Git

�� ������ [Git](https://git-scm.com/) �� ������ ������ .

���� �� ����� ��� ��� �������� , ��� �� ��� ��� ��� ���� ������� . 

</div>
<img src="pictures/gitbashsure.png">

<div  dir="rtl"  align="right">

### ������ ������� : ����� ���� � �������� 

</div>

```
mkdir git-tutorial
cd git-tutorial
```

<img src="pictures/step2.png">

<div  dir="rtl"  align="right">

### ������ ������� : ����� git repository 

</div>

```
git init
```

<img src="pictures/step3.png">


<div  dir="rtl"  align="right">

### ������ ������� : ������ �� git repository ��� ���� ����� 

</div>

```
git status
```

<img src="pictures/step4.png">

<div  dir="rtl"  align="right">

### ������ ������� : ����� ��� ���� 

</div>

```
touch file.txt
ls
```

<img src="pictures/step5.png">

<div  dir="rtl"  align="right">

### ������ ������� : ������ �� ���� repository ��� ����� ����� 

</div>
```
git status
```

<img src="pictures/step6.png">

<div  dir="rtl"  align="right">

������ : ��� ���� ��� ����� ^ ^

### ������ ������� : ����� ����� ��� ������ 

</div>

```
git add file.txt
```

<img src="pictures/step7.png">

<div  dir="rtl"  align="right">

### ������ ������� : ����� ������� � ����� 

</div>

```
git config --global user.email "YourEmail@gmail.com"
git config --global user.name "Your Name"
```

<img src="pictures/step8.png">

<div  dir="rtl"  align="right">

### ������ ������� : �����  a commit 

</div>

```
git commit -m "my first commit!"
```

<img src="pictures/step9.png">


<div  dir="rtl"  align="right">

### ������ ������� : ������ �� ���  Git 

</div>

```
git log
```

<img src="pictures/step10.png">



### ������ ������� ��� : ����� ���� � repository ��� github 

����� ���� ��� github 


<img src="pictures/step11.png">



��� ��� �� ������ repository ������ ��� ���� ������ "+" �� "new repository" . 



<img src="pictures/step11-1.png">



��� ��� �� ���� ��� �� .

<img src="pictures/step11-2.png">

<div  dir="rtl"  align="right"> 

### ������ ������� ��� : ����� ������ �� ��� � local git repository

</div> 

```
git remote add origin <link to repo>
```

<div  dir="rtl"  align="right"> 

���� ��� ��� ������ �� repository ���� �� ������� �� github 

</div>

<img src="pictures/step12.png">

<div  dir="rtl"  align="right"> 

�� ���� ������ ����� 

</div>

<img src="pictures/step12-1.png"> 

<div  dir="rtl"  align="right"> 

### ������ ������� � ����� : ��� local repository �    remot repository

</div>

```
git push -u <remote repo> <branch name>
```
��� ��� ��� ���� github ����� �� ��� �������� � ���� ������ , �� �������� . 

<img src="pictures/step13.png"> 

# � ��� �� ^ ^ 

<img src="pictures/done.png">

