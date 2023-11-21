# Linux_Labs
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
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/addIslamGroup.png?raw=true)

### 7. Modify islam's account so the password expires after 30 days
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/passwdExpireIslam.png?raw=true)

### 8. Lock bad user account so he can't log in
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/lockBadUser.png?raw=true)

### 9. Delete bad user account
####   problem apppear here: userdel: user baduser is currently used by process 40831
###    to solve it use kill command ==>sudo kill -9 PID  ===>sudo kill -9 40831
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/deletebadbutkillbefore.png?raw=true)

### 10. Delete the supplementary group called badgroup.
![UNFOUND](https://github.com/AlaaSherif55/Linux-Labs/blob/main/deletebadbutkillbefore.png?raw=true)

