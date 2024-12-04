# Linux-RedHat

# Assignment Tasks

## Task 1: File Management

1. **Navigate to your home directory (`~/`).**
   - Ensure you're in your home directory.
   
2. **Create a directory named `assignment_files`.**
   - Create the directory where all your work will reside.

3. **Inside `assignment_files`, create the following directory structure**:
   - Create the directories as per the provided structure.

4. **Create an empty file named `readme.txt` inside the `assignment_files` directory.**
   - Place the `readme.txt` file in the `assignment_files` directory.

5. **List the contents of `assignment_files` to ensure the structure is correct.**
   - Verify that the directories and `readme.txt` file exist as expected.

---

## Task 2: Bash

Write a bash script named `backup_script.sh` that performs the following tasks:

1. **Check if the `backups` directory exists inside `assignment_files`. If not, create it.**
   - Ensure the backup directory is created if it doesn't exist.

2. **Copy all `.txt` files from the `documents` directory to the `backups` directory.**
   - Move all `.txt` files from `documents` to `backups`.

3. **Append the current date and time to each file name copied to indicate the backup timestamp.**
   - Rename the files to include a timestamp of when the backup occurred.

4. **Display a message indicating the number of files backed up and their new names.**
   - Output the total number of files backed up and their new names with timestamps.

---

## Task 3: File Permissions

Navigate to the `assignment_files` directory and modify the permissions as follows:

1. **Ensure the `documents` directory is readable, writable, and executable by the owner, and readable and executable by others.**
   - Modify the permissions for `documents` to allow these settings.

2. **Ensure the `scripts` directory is readable, writable, and executable by the owner only.**
   - Set the permissions for the `scripts` directory to be exclusive to the owner.

3. **Ensure the `logs` directory is writable and executable by the owner only.**
   - Modify `logs` directory permissions for owner-only access.

4. **Ensure the `backups` directory is readable and writable by the owner only.**
   - Adjust permissions for `backups` directory to allow the owner only.

5. **Ensure all `.sh` files inside the `scripts` directory are executable by the owner only.**
   - Ensure that only the owner can execute `.sh` files inside `scripts`.

---

## Task 4: File Management

Write a bash script named `cleanup_script.sh` that performs the following tasks:

1. **Delete all `.txt` files from the `documents` directory that are older than 7 days.**
   - Clean up old `.txt` files older than 7 days.

2. **Move all `.sh` files from the `scripts` directory to the `backups` directory.**
   - Move the `.sh` scripts to `backups` for safekeeping.

3. **Display a message indicating the number of files deleted from `documents` and the number of files moved to `backups`.**
   - Show the number of deleted files and moved scripts after the cleanup process.

---

## Conclusion

This project involves basic file management tasks such as creating directories, modifying file permissions, and writing bash scripts to automate backup and cleanup tasks. Follow the instructions for each task to ensure proper completion of the assignment.
