
# Linux Command Reference

This document contains a collection of commonly used Linux commands. The commands listed here cover various operations like file management, user management, system monitoring, and version control with Git.

## File and Directory Operations

- `ls`: List files and directories in the current directory.
- `ls -sl`: List files with detailed file size information.
- `ls -all`: List all files, including hidden files.
- `cd <directory>`: Change the current directory to `<directory>`.
- `pwd`: Print the current working directory.
- `cat <file>`: Display the contents of `<file>`.
- `mkdir <directory>`: Create a new directory named `<directory>`.
- `touch <file>`: Create an empty file or update the timestamp of `<file>`.
- `rm <file>`: Remove the specified `<file>`.
- `tree`: Display directories and files in a tree-like format.

## System Information and Management

- `whoami`: Display the current logged-in user.
- `date`: Display the current date and time.
- `sudo --version`: Show the version of `sudo` installed.
- `sudo su -`: Switch to the root user.
- `sudo -i`: Start an interactive shell as the root user.
- `cat /etc/passwd`: Display the system user accounts.

## User and Group Management

- `useradd <username>`: Create a new user with the username `<username>`.
- `passwd <username>`: Set or change the password for the user `<username>`.
- `groupadd <groupname>`: Create a new group named `<groupname>`.
- `gpasswd -a <user> <group>`: Add `<user>` to the `<group>` group.
- `sudo useradd -m <username>`: Create a new user and their home directory.

## Git Version Control

- `git init`: Initialize a new Git repository.
- `git status`: Show the status of the working directory.
- `git add <file>`: Add changes from `<file>` to the staging area.
- `git commit -m "<message>"`: Commit changes with a message `<message>`.
- `git log`: View the Git commit history.
- `git log --oneline`: View a concise version of the commit history.
- `git checkout <branch>`: Switch to a specific branch.
- `git checkout -b <branch>`: Create and switch to a new branch.
- `git branch`: List all branches in the repository.

## Text Editing

- `vim <file>`: Open the file `<file>` in the `vim` editor.
- `nano <file>`: Open the file `<file>` in the `nano` editor.
- `head <file> -n <num>`: Display the first `<num>` lines of a file.
- `tail <file> -n <num>`: Display the last `<num>` lines of a file.

## Package Management

- `sudo apt install <package>`: Install a package using `apt` package manager (Debian/Ubuntu-based systems).
- `sudo yum install <package>`: Install a package using `yum` package manager (RedHat/CentOS-based systems).
  
## Network Tools

- `ping <host>`: Send ICMP echo requests to check the network connection.
- `ifconfig`: Display network interfaces and their configurations.
- `netstat`: Display network connections, routing tables, and interface statistics.

## Nginx Web Server

- `sudo apt install nginx -y`: Install Nginx web server on the system.
- `sudo service nginx start`: Start the Nginx service.
- `sudo service nginx stop`: Stop the Nginx service.
- `sudo service nginx restart`: Restart the Nginx service.

---

## Notes

- Most of the commands require `sudo` or root privileges to perform certain operations.
- Git commands listed here assume that you have initialized a Git repository and are familiar with basic Git usage.
- The commands in this document are suitable for Ubuntu/Debian-based systems, and some may differ for other Linux distributions.

Feel free to use and modify this list as needed. Enjoy your Linux experience!
