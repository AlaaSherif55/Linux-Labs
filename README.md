# Linux_Labs
## Lab 1

### 1. Install CentOS /RHEL
#### Done :)

### 2. What is the difference between cat and more command?
####   cat: 
#####       -stands for concatenate and   
#####       -It outputs the entire content of the file to the terminal.
#####       -It is not suitable for large files, as the entire content is displayed at once.
####   more:
#####       - It displays the content of the file page by page.
#####       -It is suitable for viewing large files as it loads the content incrementally.

### 3. What is the difference between rm and rmdir using man?
#### rm 
##### m - remove files or directories
##### SYNOPSIS   rm [OPTION]... [FILE]...
##### DESCRIPTION
#####     This  manual  page  documents  the GNU version of rm.  rm removes each
#####     specified file.  By default, it does not remove directories.

#### rmdir
##### rmdir - remove empty directories
##### SYNOPSIS   rmdir [OPTION]... DIRECTORY...
##### DESCRIPTION
#####     Remove the DIRECTORY(ies), if they are empty.

### 4. Create the following hierarchy under your home directory:
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-createDirectories.png?raw=true)

#### a. Remove dir11 in one-step. What did you notice? And how did you overcome that?
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-4-a.png?raw=true)

#### b. Then remove dir12 using rmdir –p command. State what happened to the
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-4-a.png?raw=true)

#### c. The output of the command pwd was /home/user. Write the absolute and relative path for the file mycv
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-4-c.png?raw=true)

### 5. Copy the /etc/passwd file to your home directory making its name is mypasswd.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-5.png?raw=true)

### 6. Rename this new file to be oldpasswd.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-6.png?raw=true)

### 7. You are in /usr/bin, list four ways to go to your home directory
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-7.png?raw=true)

### 8. List Linux commands in /usr/bin that start with letter w
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-8.png?raw=true
)

### 9. Display the first 4 lines of /etc/passwd
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-9.png?raw=true)

### 10.Display the last 7 lines of /etc/passwd
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-10..png?raw=true)

### 11.Display the man pages of passwd the command and the file sequentially in one command.
![UNFOUND]()

### 12.Display the man page of the passwd file.
![UNFOUND]()

### 13.Display a list of all the commands that contain the keyword passwd in their man page.
![UNFOUND]()



## Lab2

### 1. Create a user account with the following attribute and username: islam and Fullname/comment: Islam Askar and Password: islam
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/adduserIslam.png?raw=true)

### 2. Create a user account with the following attribute and Username: baduser and Full name/comment: Bad User and Password: baduser
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/bad%20user.png?raw=true)

### 3. Create a supplementary (Secondary) group called pgroup with group ID of 30000
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/addGroup&badGroup.png?raw=true )

### 4. Create a supplementary group called badgroup
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/addGroup&badGroup.png?raw=true )

### 5. Add islam user to the pgroup group as a supplementary group
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/addIslamGroup.png?raw=true)

### 6. Modify the password of islam's account to password
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/changeIslamPasswd.png?raw=true)

### 7. Modify islam's account so the password expires after 30 days
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/passwdExpireIslam.png?raw=true)

### 8. Lock bad user account so he can't log in
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lockBadUser.png?raw=true)

### 9. Delete bad user account
####   problem apppear here: userdel: user baduser is currently used by process 40831
####    to solve it use kill command ==>sudo kill -9 PID  ===>sudo kill -9 40831
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/deletebadbutkillbefore.png?raw=true)

### 10. Delete the supplementary group called badgroup.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/deletebadbutkillbefore.png?raw=true)

