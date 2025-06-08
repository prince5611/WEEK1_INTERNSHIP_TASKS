# Task 4: Create a New User and Group, Set Permissions, Manage Users

---

### 1. Create a new group named `mygroup`

```bash
sudo groupadd mygroup
 New password: 
Retype new password:
passwd: password updated successfully
id myuser
uid=1001(myuser) gid=1002(mygroup) groups=1002(mygroup)
sudo groupadd newgroup
sudo usermod -g newgroup myuser
sudo userdel -r myuser
userdel: myuser mail spool (/var/mail/myuser) not found
sudo groupdel mygroup
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ 