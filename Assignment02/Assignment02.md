## Assignment 02

#### 1. List the directory contents date wise sorted. ( man ls)
- ls -ltr


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


 
#### 8 Considering above directory structure , Do following operations :
i. list the directory contents of directory named
"five" from current directory (i.e. home directory).
1ii. write your name in a file named "44.txt" of
directory "four" from current directory.
iii. remove the file named "555.txt" from directory
"five" from current directory.
iv. change directory to five
one/two/three/four/five/ ).
( i.e. cd
v. write your course name in file named "3.txt" which
resides in directory "three" from current directory (i.e.
five).also read the same file.
vi. list the contents of directory "two" from current
directory (i.e. five).
vii. remove file named "222.txt" which belongs to
directory "two" from current directory (i.e. five)
viii. now change the directory to "one"
ix. remove all files only from directory named "five"
from current directory (i.e. one)
x. remove directory named "five" from current directory
(i.e. one)
xi. remove whole directory named "four" from current
directory (i.e. one)
xii. change to your home directory.

- cd /home/sunbeam/Desktop/OS Assignments/Assignment02/one/two/three/four/five | ls


#### 9 - change the time stamp of file named "3.txt" which resides in directory named "three
    - touch -d 2024/05/31 3.txt
    - 
    - cd /home/sunbeam/Desktop/OS Assignments/Assignment02/one/two/three/four/five | rm 55.txt
    -   
    - cd ../.. | cat >> 33.txt
    - 