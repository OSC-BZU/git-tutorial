

<div align="center">

# Git Tutorial for OSC in Arabic

<img src="https://s24255.pcdn.co/wp-content/uploads/2015/02/Git.png" height="250px" width="250px"> 
<div  dir=”rtl”  align=”right”> 
####ÈÑäÇãÌ ÊæÖíÍí ÕÛíÑ á git  Êã ÅÚÏÇÏå áÍÏË á OSC – BZU
</div>
</div>
<div  dir="rtl"  align="right"> 

### ÇåÏÇİ ÇáÈÑäÇãÌ 
</div>
<div  dir="rtl"  align="right"> 

1.İåã ÇÓÇÓíÇÊ Git .

2.ÇäÔÇÁ local git repository ÈÇ ÓÊÎÏÇã command line  .

3.ÊÍãíá local git repository Úáì ãæŞÚ github .

</div>
<div  dir="rtl"  align="right"> 

### ÇáÇæÇãÑ Çáãåãå İí Git 

</div>
```
git init
git status
git add <file name> 
git commit -m "your message"
git push -u <remote name> <branch name>
```
<div  dir="rtl"  align="right">

### ÇáÎØæÉ ÇáÇæáì : ÊËÈíÊ Git

Şã ÈÊÍãíá [Git](https://git-scm.com/) ãä ÇáãæŞÚ ÇáÑÓãí .

ÊÃßÏ ãä ÍÕæáß Úáì åĞÇ ÇáÇÎÊíÇÑ , áßä ßá ÔíÁ ÛíÑ åĞÇ íßæä ÇİÊÑÇÖí . 

</div>
<img src="pictures/gitbashsure.png">

<div  dir="rtl"  align="right">

### ÇáÎØæÉ ÇáËÇäíå : ÇäÔÇÁ Ïáíá á ÇáÈÑäÇãÌ 

</div>

```
mkdir git-tutorial
cd git-tutorial
```

<img src="pictures/step2.png">

<div  dir="rtl"  align="right">

### ÇáÎØæÉ ÇáËÇáËÉ : ÊåíÆÉ git repository 

</div>

```
git init
```

<img src="pictures/step3.png">


<div  dir="rtl"  align="right">

### ÇáÎØæÉ ÇáÑÇÈÚå : ÇáÊÍŞŞ ãä git repository ÇĞÇ ßÇäÊ İÇÑÛå 

</div>

```
git status
```

<img src="pictures/step4.png">

<div  dir="rtl"  align="right">

### ÇáÎØæÉ ÇáÎÇãÓÉ : ÇäÔÇÁ ãáİ İÇÑÛ 

</div>

```
touch file.txt
ls
```

<img src="pictures/step5.png">

<div  dir="rtl"  align="right">

### ÇáÎØæÉ ÇáÓÇÏÓÉ : ÇáÊÃßÏ ãä ÍÇáÉ repository ÚäÏ ÇÖÇİÉ Çáãáİ 

</div>
```
git status
```

<img src="pictures/step6.png">

<div  dir="rtl"  align="right">

ãáÇÍÙÉ : áÓÇ ÖÇíá ÓÈÚ ÎØæÇÊ ^ ^

### ÇáÎØæÉ ÇáÓÇÈÚÉ : ÇÖÇİÉ Çáãáİ Úáì ÇáãäÕÉ 

</div>

```
git add file.txt
```

<img src="pictures/step7.png">

<div  dir="rtl"  align="right">

### ÇáÎØæÉ ÇáËÇãäå : ÊåíÆÉ ÇáÇíãíá æ ÇáÇÓã 

</div>

```
git config --global user.email "YourEmail@gmail.com"
git config --global user.name "Your Name"
```

<img src="pictures/step8.png">

<div  dir="rtl"  align="right">

### ÇáÎØæÉ ÇáÊÇÓÚå : ÇäÔÇÁ  a commit 

</div>

```
git commit -m "my first commit!"
```

<img src="pictures/step9.png">


<div  dir="rtl"  align="right">

### ÇáÎØæÉ ÇáÚÇÔÑå : ÇáÊÃßÏ ãä ÓÌá  Git 

</div>

```
git log
```

<img src="pictures/step10.png">



### ÇáÎØæÉ ÇáÍÇÏíå ÚÔÑ : ÇäÔÇÁ ÍÓÇÈ æ repository Úáì github 

ÇäÔÇÁ ÍÓÇÈ Úáì github 


<img src="pictures/step11.png">



ÈÚÏ Ğáß Şã ÈÇäÔÇÁ repository ÈÇáäŞÑ Úáì ÇÚáì Çáíãíä "+" Ëã "new repository" . 



<img src="pictures/step11-1.png">



ÈÚÏ Ğáß Şã ÈæÖÚ ÇÓã áå .

<img src="pictures/step11-2.png">

<div  dir="rtl"  align="right"> 

### ÇáÎØæÉ ÇáËÇäíÉ ÚÔÑ : ÇÖÇİÉ ÇáÑÇÈØ Úä ÈÚÏ á local git repository

</div> 

```
git remote add origin <link to repo>
```

<div  dir="rtl"  align="right"> 

ÇæáÇ íÌÈ äÓÎ ÇáÑÇÈØ ãä repository ÇáÊí Êã ÇäÔÇÆåÇ İí github 

</div>

<img src="pictures/step12.png">

<div  dir="rtl"  align="right"> 

Ëã äŞæã ÈÇáÃãÑ ÃÚáÇå 

</div>

<img src="pictures/step12-1.png"> 

<div  dir="rtl"  align="right"> 

### ÇáÎØæÉ ÇáÇÎíÑå æ ÇÎíÑÇ : ÑİÚ local repository á    remot repository

</div>

```
git push -u <remote repo> <branch name>
```
ÈÚÏ Ğáß Óæİ íŞæã github ÈÓÃáß Úä ÇÓã ÇáãÓÊÎÏã æ ßáãÉ ÇáãÑÑæ , Şã ÈÇÏÎÇáåÇ . 

<img src="pictures/step13.png"> 

# æ åÇÖ åæ ^ ^ 

<img src="pictures/done.png">

