# Lecture 4 review note
  
### Shell command list
- pwd
- cd & ls
- auto completion & past command & clear
- cp
- mv
- rm
- mkdir
- wildcards

---

### pwd

pwd shows the current path in a hierarchical directory.

---

#### cd & ls

cd means change directory. If you type ***cd dir*** the current directory will change into ***dir***.

ls shows a list of files and directories. 
ls -l shows detailed information in long format.
ls -lh shows same things, but size in units.

ls -l format : filePermissions  owener  group  size  modificationTime fileName

---

### auto completion & past command & clear

If you press "tab" key  you can use auto completion.

If you press "up arrow" key you can check past command.

If you type ***clear*** you can clean up your past commands and results.

---

### cp

You can use cp when you want to copy files and directories.

cp *file1 file2*: file1 file2 :Copies the contents of file1 into file2. If file 2 does not exist, it is created

cp *file1 dir1*: Copy the contents of file1 insdie of directort *dir1*

cp -R *dir1 dir2*: Copy the contents of the directory *dir1*. If directory *dir2* does not exist, it is created. Otherwise, it creates a directory named *dir1* within directory *dir2*.

---

### mv

You can move files and directories or rename them by using mv

mv *file1 file2*: If *file2* does not exist, then *file1* is renamed *file2*. If *file2* exists, its contents are silently replaced with the contents of *file1*.

mv *file1 file2 dir1*: The files *file1* and *file2* are moved to directory *dir1*. If *dir1* does not exist, mv will exit with an error.

mv *dir1 dir2*: If *dir2* does not exist, then *dir1* is renamed *dir2*. If *dir2* exists, the directory *dir1* is moved within directory *dir2*.

---

### rm

You can delete files and directories permantely and irreversevely by using rm.

rm *file1 file2*: Delete *file1* and *file2*.

rm -r *dir1 dir2*: Directories *dir1* and *dir2* are deleted along with all of their contents.

**Be careful with rm!**

Linux does not have an undelete command. Once you delete something with rm, it's gone. You can inflict terrific damage on your system with rm if you are not careful, particularly with wildcards.

---

### mkdir

You can nake a new directory by using mkdir.

---





