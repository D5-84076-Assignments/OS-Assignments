# Assignment 04

i) count the no. of words ,characters and lines from above 2 file.(man wc)
  - **wc data**
  6  25 145 data

ii) list the lines having word "files" (man grep)
   **ls | grep "files" data**
files have permissions.
files have inode no.
files have size.
there are several types of files

iii)list the lines having word "file" (man grep)
    **- ls | grep "file" data**
In Linux everything is file
files have permissions.
files have inode no.
files have size.
there are several types of files

list the lines which don't have word "files" (man grep)
  **NOTES**
   **In Linux, to find lines in a file that do not contain certain keywords, you can use the grep command with the -v option. The -v option inverts the match, meaning it will select lines that do not match the specified pattern.**
        **grep -v "keyword" filename**

        **<i>ls | grep -v "file" data</i>**

Linux is open source.

list the lines having word "have" . (man grep)
 - **ls | grep "have" data**
  _output_
files have permissions.
files have inode no.
files have size.

list the lines starts with letter "f" (man grep)
 - **ls | grep "^f" data**
  
  _Output_
files have permissions.
files have inode no.
files have size.

list the lines ends with "." (man grep)
 - **ls | grep ".$" data**
  _Output_

 Linux is open source.
 In Linux everything is file
 files have permissions.
 files have inode no.
 files have size.
 there are several types of files

list only first two lines.(man head)
 - **<pre>head -2 data**
  _Output_
Linux is open source.
In Linux everything is file
</pre>
list only last three lines.(man tail)
  - tail -3 data
_ _Output__
  - files have inode no.
files have size.
there are several types of files

list line no.3,4 and 5 . (man head and tail)
 - head -5 data | tail -3 data
_Output_
head -5 data | tail -3 data
files have inode no.
files have size.
there are several types of files
