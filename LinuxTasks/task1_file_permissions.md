# Task 1: File Creation & Permission Assignment

## Objective:
Create a file, assign specific permissions (read, write, execute) to different user categories (owner, group, others), and verify the permissions using Linux commands.

---

## Commands Executed:

```bash
# Create an empty file named testfile.txt
touch testfile.txt

# Set permissions:
# Owner (user): read, write, execute (rwx)
# Group: read, write (rw-)
# Others: read only (r--)
chmod u=rwx,g=rw,o=r testfile.txt

# List files with detailed information to verify permissions
ls -l
