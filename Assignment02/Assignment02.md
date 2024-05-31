## Assignment 02

#### 1. List the directory contents date wise sorted. ( man ls)
- ls -l | sort


#### 2 - List the directory contents size wise sorted.(man ls)
-  ls -lSr


#### 3 - List directory contents along with their inode no. (man
ls)

-  ls -i


#### 4 - List the contents of the subdirectory.
 - ls -R


#### 5 - Create a file, write your surname and name in it and save.
 -i. now open the same file and add your address in it and
save.
 -ii. reopen the same file and check your name and address in it.

  >> Command > cat intro
               cat 
               cat >> intro
               cat > intro


#### 6  - how to change the time stamp of file (man touch)



#### 7 - Create directory structure : Give following commands ,
-> mkdir one
-> cd one
-> touch 1.txt 11.txt 111.txt
-> mkdir two
-> cd two
-> touch 2.txt 22.txt 222.txt
-> mkdir three
-> cd three
-> touch 3.txt 33.txt 333.txt
-> mkdir four
-> cd four
-> touch 4.txt 44.txt 444.txt
-> mkdir five
-> cd five
-> touch 5.txt 55.txt 555.txt
-> **cd ~** (i.e. go to your home directory)


#### 9 - change the time stamp of file named "3.txt" which resides in directory named "three
    - touch -d 2024/05/31 3.txt
