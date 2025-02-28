# OPERATING_SYSTEMS_LAB
> ## Exp1: basics of unix commands
> ### PROCEDURE: Login into the ubuntu terminal use Ctrl + Alt + t windows shortcut key or   go to activity bar search for terminal and mouse click the terminal open. 
> ### Commands with Descriptions
> ### GENERAL COMMANDS
```unix
  date
  Used to display the current system date and time.
  date +%D
  Displays date only
  date +%T
  Displays time only
  date +% Y
  Displays the year part of date
  date +% H
  Displays the hour part of time
  cal
  Calendar of the current month
  cal year
  Displays calendar for all months of the specified year
  cal month year
  Displays calendar for the specified month of the year
  who
  Login details of all users such as their IP, Terminal No, User name,
  who am i
  Used to display the login details of the user
  tty
  Used to display the terminal name
  uname
  Displays the Operating System
  unameOperating System Lab Manual Department of CSE, SRIT, ATP
  Prepared by Mr. M. Narasimhulu, 4
  Shows version number of the OS (kernel).
  uname –n
  Displays domain name of the server
  echo "txt"
  Displays the given text on the screen
  echo $HOME
  Displays the user's home directory
  bc
  Basic calculator. Press Ctrl+d to quit
  lpfile
  Allows the user to spool a job along with others in a print queue.
  man cmdname
  Manual for the given command. Press q to exit
  history
  To display the commands used by the user since log on.
  exit
  Exit from a process. If shell is the only process then logs out
```
> ### DIRECTORY COMMANDS
  ```unix
  pwd
  Path of the present working directory
  mkdir dir
  A directory is created in the given name under the current directory
  mkdir dir1 dir2
  A number of sub-directories can be created under one stroke
  cd subdir
  Change Directory. If the subdir starts with / then path starts from root (absolute)
  otherwise from current working directory.
  Cd
  To switch to the home directory.
  cd /
  To switch to the root directory.
  cd ..
  To move back to the parent directory
  rmdir subdir
  Removes an empty sub-directory.
  ```
> ### FILE COMMANDS
  ```unix
  cat >filename
  To create a file with some contents.
  To end typing press
  Ctrl+d.
  The >symbol means redirecting output to a file. (<for input)
  cat filename
  Displays the file contents.
  cat >>filename
  Used to append contents to a file
  cp src des
  Copy files to given location. If already exists, it will be overwritten
  cp –i src des
  Warns the user prior to overwriting the destination file
  cp –r src des
  Copies the entire directory, all its sub-directories and files.
  mv old new
  To rename an existing file or directory. –i option can also be used
  mv f1 f2 f3 dir
  To move a group of files to a directory.
  mv –v old new Di
  Display name of each file as it is moved.
  rm file
  Used to delete a file or group of files. –i option can also be used
  rm *
  To delete all the files in the directory.
  rm –r *
  Deletes all files and sub-directories
  rm –f *
  To forcibly remove even write-protected files
  ls
Lists all files and subdirectories (blue colored) in sorted Order
ls name
To check whether a file or directory exists.
ls name *
Short-hand notation to list out filenames of a specific pattern.
ls –a
Lists all files including hidden files (files beginning with .)
ls –x dirname
To have specific listing of a directory.
ls –R
Recursive listing of all files in the subdirectories
ls –l
Long listing showing file access rights (read/write/execute-rwx for user/group/others-
ugo).
cmp file1 file2
Used to compare two files. Displays nothing if files are identical.
Wc file It produces a statistics of lines (l), words(w), and characters(c).
chmod perm file
Changes permission for the specified file. (r=4, w=2, x=1)
chmod 740 file
sets all rights for user, read only for groups and no rights for others
```
> # BASIC UNIX COMMANDS PRACTISE OUTPUT
> ## GENERAL  COMMANDS OUTPUTS 
### DATE COMMAND OUTPUT
![date command output](date.png)   
### DATE COMMAND OUTPUT
![date command output](date1.png)
### DATE HOUR COMMAND OUTPUT
![date command output](date2.png)
### DATE TIME COMMAND OUTPUT
![date command output](date3.png)
### DATE YEAR COMMAND OUTPUT
![date command output](date4.png)
### DATE COMMAND MANUAL
![date command manual](mandate.png)
### CAL COMMAND OUTPUT
![cal command output](cal.png)
### CAL YEAR COMMAND OUTPUT
![cal YEAR command manual](calyear.png)
### CAL MONTH COMMAND OUTPUT
![cal month command output](calmonthyear.png)
### CAL COMMAND MANUAL
![cal command manual](mancal.png)
### WHO COMMAND OUTPUT 
![who command output](who.png)
### WHOAMI COMMAND OUTPUT
![whoami command output](whoami.png)
### WHO COMMAND MANUAL 
![who command output](manwho.png)
### TTY COMMAND OUTPUT -TERMINAL NAME-
![tty command output](tty.png)
### TTY COMMAND MANUAL
![tty command manual](mantty.png)
### UNAME COMMAND OUTPUT
![uname command output](uname.png)
### UNAME-R COMMAND OUTPUT
![uname-r command output](uname-r.png)
### UNAME-N COMMAND OUTPUT
![uname-n command output](uname-n.png)
### UNAME-N COMMAND MANUAL
![uname command manual](manuname.png)
### ECHO COMMAND OUTPUT
![echo command output](echo.png)
### ECHO COMMAND MANUAL
![echo command manual](manecho.png)
### ECHO $HOME COMMAND OUTPUT
![echo$home command output](echo$HOME.png)
### ECHO $ COMMAND MANUAL 
![echo $ command manual](manecho.png)
### BC - BASIC CALCULATOR COMMAND OUTPUT
![bc command output](bc.png)
### BC - BASIC CALCULATOR COMMAND MANUAL
![bc command manual](manbc.png)
> ## IP FILE COMMANDS
### HISTORY COMMAND OUTPUT
![history command output](history.png)
### HISTORY COMMAND MANUAL 
![history command manual](manhistory.png)
### EXIT COMMAND OUTPUT
![exit command output](exit.png)
### EXIT COMMAND MANUAL
![exit command manual](manexit.png)
> ## DIRECTIORY COMMANDS
### PWD COMMAND OUTPUT
![pwd command output](pwd.png)
### PWD COMMAND MANUAL
![pwd command manual](manpwd.png)
### MKDIR COMMAND OUTPUT
![mkdir command output](mkdir.png)
### MKDIR COMMAND MANUAL
![mkdir command manual](manmkdir.png)
### CD COMMAND OUTPUT
![cd command output](cd.png)
### CD SUBDIR COMMAND OUTPUT
![cd subdir command output](cdsubdir.png)
### CD.. COMMAND OUTPUT
![cd.. command output](cd...png)
### CD COMMAND MANUAL
![cd command manual](mancd.png)
### RMDIR COMMAND OUTPUT
![rmdir command output](rmdir.png)
### RMDIR COMMAND MANUAL
![rmdir command manual](manrmdir.png)
> ## FILE COMMANDS
### CAT COMMAND OUTPUT
![cat command output](cat.png)
### CAT FILENAME COMMAND OUTPUT
![cat filename command output](catfilename.png)
### CAT >> FILENAME COMMAND OUTPUT
![cat >> filename command output](cat2.png)
### CAT COMMAND MANUAL 
![cat command manual](mancat.png)
### CP COMMAND OUTPUT
![cp command output](cp.png)
### CP -I COMMAND OUTPUT
![cp -i command output](cp-i.png)
### CP -R COMMAND OUTPUT
![cp -r command output](cp-r.png)
### CP COMMAND MANUAL
![cp command manual](mancp.png)
### MV OLD NEW COMMAND OUTPUT
![mv command output](mv.png)
### MV -V OLD NEW COMMAND OUTPUT
![mv command output](mv1.png)
### MV COMMAND MANUAL
![mv command manual](manmv.png)
### RM FILE COMMAND OUTPUT
![rm file command output](rmfile.png)
### RM * COMMAND OUTPUT
![rm * command output](rm1.png)
### RM -R * COMMAND OUTPUT
![rm -r * command output](rm-r.png)
### RM -F * COMMAND OUTPUT
![rm -f * command output](rm-f.png)
### RM COMMAND MANUAL
![rm command manual](manrm.png)
### LS COMMAND OUTPUT
![ls command output](ls.png)
### LS NAME COMMAND OUTPUT
![ls name command output](lsname.png)
### LS NAME * COMMAND OUTPUT
![ls name * command output](lsname2.png)
### LS - A COMMAND OUTPUT
![ls - a command output](ls-a.png)
### LS -X DIR NAME COMMAND OUTPUT
![ls -x dir command output](ls-x.png)
### LS -R COMMAND OUTPUT
![ls -r command manual](ls-R.png)
### LS - L COMMAND OUTPUT
![ls -l command output](ls-l.png)
### LS COMMAND MANUAL
![ls command manual](manls.png)
### CMP FILE COMMAND OUTPUT
![cmp file command output](cmpfile.png)
### CMP COMMAND MANUAL
![cmp command manual](mancmp.png)
### CHMOD 740 FILE COMMAND OUTPUT
![chmod 740 file command output](chmod740file.png)
### CHMOD COMMAND MANUAL
![chmod command manual](manchmod.png)


> ## Result
> Thus the study of Basic UNIX commands has been completed successfully.
