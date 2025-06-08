# Task 5: Basic Linux File and Directory Commands

## 📁 Commands Practiced

| Command | Description |
|--------|-------------|
| `ls` | Lists files in the current directory |
| `ls -l` | Lists with details like permissions, size, and owner |
| `ls -a` | Lists all files including hidden ones |
| `cd [directory]` | Changes current directory |
| `mkdir [name]` | Creates a new directory |
| `touch [filename]` | Creates an empty file |
| `cat [filename]` | Displays file content |
| `mv [src] [dest]` | Moves or renames a file/directory |
| `cp [src] [dest]` | Copies a file |
| `rm [filename]` | Deletes a file |
| `rm -r [dirname]` | Deletes a directory and its contents |
| `rmdir [dirname]` | Deletes an empty directory |

## 🧪 Commands Used

```bash
mkdir mytestdir
cd mytestdir
touch file1.txt file2.txt
ls -l
mv file1.txt renamed_file.txt
cp renamed_file.txt copy_file.txt
cat renamed_file.txt
rm renamed_file.txt
cd ..
rm -r mytestdir

sudo groupadd devgroup
sudo useradd -m -g devgroup devuser
sudo passwd devuser
id devuser
sudo usermod -aG sudo devuser
sudo userdel -r devuser
