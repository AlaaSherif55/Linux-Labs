# Linux_Labs
## Lab 1

### 1. Install CentOS /RHEL
![UNFOUND]()
### 2. What is the difference between cat and more command?
![UNFOUND]()
### 3. What is the difference between rm and rmdir using man?
![UNFOUND]()
### 4. Create the following hierarchy under your home directory:
![UNFOUND]()

#### a. Remove dir11 in one-step. What did you notice? And how did you overcome that?
![UNFOUND]()
#### b. Then remove dir12 using rmdir –p command. State what happened to the
![UNFOUND]()

#### c. The output of the command pwd was /home/user. Write the absolute and relative path for the file mycv
![UNFOUND]()
### 5. Copy the /etc/passwd file to your home directory making its name is mypasswd.
![UNFOUND]()
### 6. Rename this new file to be oldpasswd.
![UNFOUND]()
### 7. You are in /usr/bin, list four ways to go to your home directory
![UNFOUND]()
### 8. List Linux commands in /usr/bin that start with letter w
![UNFOUND]()
### 9. Display the first 4 lines of /etc/passwd
![UNFOUND]()
### 10.Display the last 7 lines of /etc/passwd
![UNFOUND]()
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

