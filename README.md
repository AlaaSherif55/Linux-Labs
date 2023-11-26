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
#####     can't remove use rmdir because dir11 is not empty, overcome this problem by use rm -r 
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-4-a.png?raw=true)

#### b. Then remove dir12 using rmdir –p command. State what happened to the
#####    can't because it remove the home directory and this is not valid
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
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-11.png?raw=true)
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-11-b.png?raw=true)

### 12.Display the man page of the passwd file.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-12-a.png?raw=true)
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-12-b.png?raw=true)

### 13.Display a list of all the commands that contain the keyword passwd in their man page.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab1-13.png?raw=true
)



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
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/deleteBadGroup.png?raw=true)


### 13. Create a folder called myteam in your home directory and change its permissions to read only for the owner.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab2-13.png?raw=true)

### 14. Log out and log in by another user
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab2-14.png?raw=true)

### 15. Try to access (by cd command) the folder (myteam)
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab2-15.png?raw=true)

### 16. Using the command Line


#### a- Change the permissions of oldpasswd file to give owner read and write permissions and for group write and execute and execute only for the others(using chmod in 2 different ways)
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab2-16-a.png?raw=true
)
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab2-16-a-631.png?raw=true)
#### b-Change your default permissions to be as above.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab2-16-b.png?raw=true)

#### c-What is the maximum permission a file can have, by default when it is just created? And what is that for directory.
#### The default permissions for a file are typically 666 (rw-rw-rw-),
#### The default permissions for a directory are usually 777 (rwxrwxrwx). However, the umask value is subtracted from these

#### d-Change your default permissions to be no permission to everyone then create a directory and a file to verify.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab2-16-d.png?raw=true)

### 17. What are the minimum permission needed for:
#### Copy a directory (permission for source directory and permissions for target parent directory)
###### source directory ===> --x 
###### target parent directory ===> -wx

#### Copy a file (permission for source file and and permission for target parent directory)
###### file ===> r-- 
###### source directory ===> --x
###### target parent directory ===> -wx

#### Delete a file
###### file ===> ---
###### source directory ===> -wx


#### Change to a directory
###### --x

#### List a directory content (ls command)
###### r--

#### View a file content (more/cat command)
###### r--

#### Modify a file content
###### if interactive tool like vi need rw
###### if non interative tool vi need w

### 18. Create a file with permission 444. Try to edit in it and to remove it? Note what happened.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab2-18.png?raw=true
)

### 19. What is the difference between the “x” permission for a file and for a directory?
###### x for file mean run this file 
###### x for directory mean can make cd to it and if rx can make ls -l




## lab3

### 1. Using vi write your CV in the file mycv. Your CV should include your name, age, school,college, experience,...
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab3-1.png?raw=true44
)
### 2. Open mycv file using vi command then: Without using arrows state how to:
#### a. Move the cursor down one line at time.
##### j
#####
#### b. Move the cursor up one line at time.
##### k
#####
#### c. Search for word age
##### /age
#####
#### d. Step to line 5 (assuming that you are in line 1 and file is more than 5 lines).
##### :5
#####
#### e. Delete the line you are on and line 5.
#####  D
#####
#### f. How to step to the end of line and change to writing mode in one-step.
#####  $
#####

### 3. List the available shells in your system.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab3-3.png?raw=true
)

### 4. List the environment variables in your current shell.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab3-4.png?raw=true
)

### 5. List all of the environment variables for the bash shell.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab3-5a.png?raw=true)

### 6. What are the commands that list the value of a specific variable?
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab3-6.png?raw=true)

### 7. Display your current shell name.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab3-7.png?raw=true)

### 8.. State the initialization files of: sh, ksh, bash.
####    /etc/profile (system-wide)
####     ~/.bash_profile or ~/.bash_login or ~/.profile (user-specific, only the first one found is executed)
####     ~/.bashrc (sourced by interactive non-login shells)

### 9.Edit in your profile to display date at login and change your prompt permanently.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab3-9.png?raw=true)
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab3-9-b.png?raw=true)
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab3-a.png?raw=true)
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/image.png?raw=true)

### 10.Execute the following command :
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab3-10.png?raw=true)

### 11.Create a Bash shell alias named ls for the “ls –l” command
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lab3-11.png?raw=true
)

### lab 4

#### 1.List the user commands and redirect the output to /tmp/commands.list
![UNFOUND]()

#### 2.Count the number of user commands
![UNFOUND]()

#### 3.Get all the users names whose first character in their login is ‘g’.
![UNFOUND]()

#### 4.Get the logins name and full names (comment) of logins starts with “g”.
![UNFOUND]()

#### 5.Save the output of the last command sorted by their full names in a file.
![UNFOUND]()

#### 6.Write two commands: first: to search for all files on the system that named .bash_profile. Second: sorts the output of ls command on / recursively, Saving their output and error in 2 different files and sending them to the background.
![UNFOUND]()

#### 7. Display the number of users who is logged now to the system.
![UNFOUND]()

#### 8. Display lines 7 to line 10 of /etc/passwd file
![UNFOUND]()

#### 9. What happens if you execute:cat filename1 | cat filename2/ls | rm/ ls /etc/passwd | wc –l
![UNFOUND]()

#### 10. Issue the command sleep 100.
![UNFOUND]()

#### 11. Stop the last command.
![UNFOUND]()

#### 12. Resume the last command in the background
![UNFOUND]()

#### 13. Issue the jobs command and see its output.
![UNFOUND]()

#### 14. Send the sleep command to the foreground and send it again to the background.
![UNFOUND]()

#### 15. Kill the sleep command.
![UNFOUND]()

#### 16. Display your processes only
![UNFOUND]()

#### 17. Display all processes except yours
![UNFOUND]()

#### 18. Use the pgrep command to list your processes only
![UNFOUND]()

#### 19. Kill your processes only.
![UNFOUND]()




