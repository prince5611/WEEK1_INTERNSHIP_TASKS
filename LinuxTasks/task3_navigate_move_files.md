# Task 3: Navigate & Move Files

---

### 1. Show current directory

```bash
pwd
/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ ls -a
.  ..  task1_file_permissions.md  task2_basic_linux_commands.md
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ mkdir dir1
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ cd dir1
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks/dir1$ touch file1.txt
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks/dir1$ cd ..
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ mv dir1/file1.txt .
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$ ls
dir1  file1.txt  task1_file_permissions.md  task2_basic_linux_commands.md
prince@DESKTOP-DMGF6K2:/mnt/c/Users/ARISE/Desktop/Week1_Internship_Tasks/LinuxTasks$