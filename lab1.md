# Lab1
## Report
[link](https://ucsd-cse15l-s24.github.io/week1/index.html#lab-report-1---remote-access-and-filesystem-week-1)
* *no arguments* in the order of `cd, ls, and cat`

**the absolute path and to the working directory was right before the command was run** : 

1. `C:\Users\NingqiShen`
2. `C:\Users\NingqiShen`
3. `C:\Users\NingqiShen`

The current working directory 
`C:\Users\NingqiShen`

---

A sentence or two explaining why you got that output
> no error


![image](https://github.com/Klein-Shen/cse15l-lab-reports/assets/165833763/39ded354-c79a-46c3-8940-b8d268bf5407)


No arguments for `cd` means change nothing,
so it means `cd` without any arguments will just maintain at the current working directory.

> no error


![image](https://github.com/Klein-Shen/cse15l-lab-reports/assets/165833763/4cda31c7-c9c0-40ea-be2f-7a1888261b9e)


No arguments for `ls` means list the files or folders in the current working directory.

> no error


![image](https://github.com/Klein-Shen/cse15l-lab-reports/assets/165833763/dffd26fc-9442-4f8a-bdd1-4520e7dcb24c)


No arguments for `cat`, from the image, it looks like the terminal was waiting for me to provide something. 
And it did not print anything.


* *a path to a directory as an argument* in the order of **`cd, ls, and cat`**

**the absolute path to the working directory was right before the command was run** : 

1. C:\Users\NingqiShen
2. C:\Users\NingqiShen\Desktop
3. C:\Users\NingqiShen\Desktop
---
> no error


![image](https://github.com/Klein-Shen/cse15l-lab-reports/assets/165833763/1804811a-f6e0-46d2-a652-3741ef69fb38)


A path to a directory as an argument for `cd` means change the working directory to the new path what I provided afer the `cd`.

> no error


![image](https://github.com/Klein-Shen/cse15l-lab-reports/assets/165833763/2d231e9a-d3f6-4de7-bf54-2f828197c79a)


A path to a directory as an argument for `ls` means list the files or folders in the new path without changing the working directory.

> error:
`cat` want to get the content, but there is no content in the path since the path point a folder. So we need to point to a file, then `cat` will work.

![image](https://github.com/Klein-Shen/cse15l-lab-reports/assets/165833763/3ecb058d-7382-4c4f-b117-2809bb66748d)


A path to a directory as an argument for `cat` from the image, it looks like the terminal rejected us to visit this new path as a folder.
was waiting for me to provide something. And it gave the exceptions.


* *a path to a file as an argument* in the order of **`cd, ls, and cat`**

**the absolute path to the working directory was right before the command was run** : 

1. C:\Users\NingqiShen\Desktop\hello\word\helloworld
2. C:\Users\NingqiShen\Desktop\hello\word\helloworld
3. C:\Users\NingqiShen\Desktop\hello\word\helloworld
---


> error:
If the `cd` command points to the correct path, the command will be executed, otherwise an error will be reported.

![image](https://github.com/Klein-Shen/cse15l-lab-reports/assets/165833763/77f6124d-974e-402f-b63b-55b2471af089)


A path to a file as an argument for `cd` gave the exceptions and said that the path does not exist. Maybe I think the cd cannot open a file.


> no error


![image](https://github.com/Klein-Shen/cse15l-lab-reports/assets/165833763/478f6f2f-744a-431c-95b3-b0743e6bd405)


A path to a file as an argument for `ls` it does list the file, but in this folder there are some other files or folders, but it only showed the files as a lsit what I put after the command `HelloWorld.java`.


> no error


![image](https://github.com/Klein-Shen/cse15l-lab-reports/assets/165833763/a93d5294-cd9f-47e0-935f-51aa9d554ed0)


A path to a file as an argument for `cat` from the image, it obviously printed the code in the `HelloWorld.java`.


