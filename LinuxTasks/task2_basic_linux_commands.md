# Task 2: Basic Linux Commands

## Commands and Outputs

1. **List files and folders**

```bash
ls
prince@DESKTOP-DMGF6K2:~/internship_test$ cd /mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ ls
task1_file_permissions.md
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ mkdir myfolder
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ cd myfolder
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks/myfolder$ touch newfile.txt
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks/myfolder$ ls -l
total 0
-rwxrwxrwx 1 prince prince 0 Jun  7 16:55 newfile.txt
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks/myfolder$ cd ..
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ rm myfolder/newfile.txt
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ rmdir myfolder
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ 