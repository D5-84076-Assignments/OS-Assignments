# Assignment 04

ls | grep "files" data
 1908  ls | grep "file" data
 1909  ls | grep -v "file" data
 1910  ls | grep "have" data
 1911  ls | grep "^f" data
 1912  ls | grep "$." data
 1913  ls | grep ".$" data


i.

i)count the no. of words ,characters and lines from above 2 file.(man wc)
 - wc data
    6  25 145 data

ii)list the lines having word "files" (man grep)
 - **ls | grep "files" data**
  _Output_
  files have permissions.
files have inode no.
files have size.
there are several types of files


list the lines having word "file" (man grep)
 - **ls | grep "file" data**
  _Output_
  In Linux everything is file
files have permissions.
files have inode no.
files have size.
there are several types of files

list the lines which don't have word "files" (man grep)
 - **ls | grep -v "files" data**
 _Output_
 Linux is open source.
In Linux everything is file

list the lines having word "have" . (man grep)
 - **grep "have" data**
  _Output_
  files have permissions.
files have inode no.
files have size.

list the lines starts with letter "f" (man grep)
 - **grep "^f" data**
  _Output_
  files have permissions.
files have inode no.
files have size.

list the lines ends with "." (man grep)
 - **grep ".$" data**
  _Output_
  Linux is open source.
In Linux everything is file
files have permissions.
files have inode no.
files have size.

list only first two lines.(man head)
 - **head -2 data**
  _Output_
  Linux is open source.
In Linux everything is file

list only last three lines.(man tail)
 - **tail -3 data**
  _Output_
  files have inode no.
files have size.
there are several types of files

  
list line no.3,4 and 5 . (man head and tail)
- **head -5 data |  tail -3 data**
  _Output_
  files have inode no.
files have size.
there are several types of files
