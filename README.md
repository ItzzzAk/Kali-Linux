# Common Linux Commands Cheat Sheet

This is a collection of commonly used Linux terminal commands along with their explanations. These commands will help you navigate and perform basic tasks in the Linux terminal environment.

## Command List

### 1. `sudo`
- **Full form**: Super User DO
- **Purpose**: Execute a command with superuser (root) privileges.
- **Example**: `sudo apt update`

### 2. `apt`
- **Full form**: Advanced Package Tool
- **Purpose**: A package manager for Debian-based systems used to install, update, or remove packages.
- **Common Commands**:
  - **Update package list**: `sudo apt update`
  - **Upgrade installed packages**: `sudo apt upgrade`
  - **Install a package**: `sudo apt install <package_name>`
  - **Remove a package**: `sudo apt remove <package_name>`

### 3. `cd`
- **Full form**: Change Directory
- **Purpose**: Navigate between directories.
- **Example**: `cd /home/user/Documents`

### 4. `ls`
- **Full form**: List
- **Purpose**: Lists the contents of a directory.
- **Example**: `ls`

### 5. `pwd`
- **Full form**: Print Working Directory
- **Purpose**: Shows the current directory's full path.
- **Example**: `pwd`

### 6. `mkdir`
- **Full form**: Make Directory
- **Purpose**: Creates a new directory.
- **Example**: `mkdir new_folder`

### 7. `rm`
- **Full form**: Remove
- **Purpose**: Removes files or directories.
- **Example**:
  - Remove a file: `rm filename.txt`
  - Remove a directory: `rm -r foldername`

### 8. `cp`
- **Full form**: Copy
- **Purpose**: Copies files or directories.
- **Example**: `cp file1.txt /home/user/backup/`

### 9. `mv`
- **Full form**: Move
- **Purpose**: Moves or renames files or directories.
- **Example**: `mv file.txt /home/user/Documents/`

### 10. `chmod`
- **Full form**: Change Mode
- **Purpose**: Changes the permissions of a file or directory.
- **Example**: `chmod 755 script.sh`

### 11. `chown`
- **Full form**: Change Owner
- **Purpose**: Changes the ownership of a file or directory.
- **Example**: `sudo chown user:user file.txt`

### 12. `nano`
- **Purpose**: A simple text editor used directly in the terminal.
- **Example**: `nano file.txt`

### 13. `cat`
- **Full form**: Concatenate
- **Purpose**: Displays the contents of a file.
- **Example**: `cat file.txt`

### 14. `top`
- **Purpose**: Displays real-time system processes and resource usage.
- **Example**: `top`

### 15. `df`
- **Full form**: Disk Filesystem
- **Purpose**: Shows disk space usage of file systems.
- **Example**: `df -h`

### 16. `ps`
- **Full form**: Process Status
- **Purpose**: Lists currently running processes.
- **Example**: `ps aux`

### 17. `kill`
- **Purpose**: Terminates a process using its Process ID (PID).
- **Example**: `kill 1234`

### 18. `ifconfig`
- **Full form**: Interface Config
- **Purpose**: Displays or configures network interfaces.
- **Example**: `ifconfig`

### 19. `wget`
- **Purpose**: Downloads files from the web via HTTP, HTTPS, or FTP.
- **Example**: `wget https://example.com/file.zip`

### 20. `tar`
- **Full form**: Tape Archive
- **Purpose**: Archives or extracts `.tar` files.
- **Example**: Extract an archive: `tar -xvf archive.tar`

---

## Additional Resources

- To learn more about any command, use the `man` (manual) command: `man <command_name>`
  - Example: `man sudo`

Feel free to explore the man pages to get more detailed explanations of each command and its options.
