# Linux Commands Cheat Sheet

## File and Directory Operations

- **ls**: <sub><sup> List directory contents. </sup></sub>
- **cd \<directory>**: <sub><sup> Change the current directory. </sup></sub>
- **pwd**: <sub><sup> Print the current working directory. </sup></sub>
- **mkdir \<directory>**: <sub><sup> Create a new directory. </sup></sub>
- **rmdir \<directory>**: <sub><sup> Remove an empty directory. </sup></sub>
- **rm \<file>**: <sub><sup> Remove a file. </sup></sub>
- **cp \<source> \<destination>**: <sub><sup> Copy files or directories. </sup></sub>
- **mv \<source> \<destination>**: <sub><sup> Move or rename files or directories. </sup></sub>
- **touch \<file>**: <sub><sup> Create an empty file. </sup></sub>
- **cat \<file>**: <sub><sup> Display file content. </sup></sub>
- **nano \<file>**: <sub><sup> Open a file in the Nano text editor. </sup></sub>
- **vi \<file>**: <sub><sup> Open a file in the Vi text editor. </sup></sub>

## System Information

- **uname -a**: <sub><sup> Display system information. </sup></sub>
- **hostname**: <sub><sup> Display the system hostname. </sup></sub>
- **who**: <sub><sup> Show who is logged on. </sup></sub>
- **top**: <sub><sup> Display Linux processes. </sup></sub>
- **df**: <sub><sup> Show disk space usage. </sup></sub>
- **free**: <sub><sup> Display memory usage. </sup></sub>

## User Management

- **useradd \<username>**: <sub><sup> Add a new user. </sup></sub>
- **passwd \<username>**: <sub><sup> Change user password. </sup></sub>
- **userdel \<username>**: <sub><sup> Delete a user. </sup></sub>
- **usermod \<options> \<username>**: <sub><sup> Modify user properties. </sup></sub>
- **su \<username>**: <sub><sup> Switch user. </sup></sub>
- **sudo \<command>**: <sub><sup> Execute a command as a superuser. </sup></sub>

## Package Management

- **apt-get update**: <sub><sup> Update package index. </sup></sub>
- **apt-get upgrade**: <sub><sup> Upgrade installed packages. </sup></sub>
- **apt-get install \<package>**: <sub><sup> Install a package. </sup></sub>
- **apt-get remove \<package>**: <sub><sup> Remove a package. </sup></sub>
- **apt-cache search \<keyword>**: <sub><sup> Search for a package. </sup></sub>
- **dpkg -i \<package. </sup></sub>deb>**: <sub><sup> Install a local . </sup></sub>deb package. </sup></sub>

## Network Operations

- **ifconfig**: <sub><sup> Display network interface information. </sup></sub>
- **ping \<host>**: <sub><sup> Send ICMP echo requests to a host. </sup></sub>
- **traceroute \<host>**: <sub><sup> Trace the route to a host. </sup></sub>
- **netstat**: <sub><sup> Show network statistics. </sup></sub>
- **wget \<URL>**: <sub><sup> Download files from the web. </sup></sub>
- **ssh \<username>@\<hostname>**: <sub><sup> Connect to a remote host via SSH. </sup></sub>
- **scp \<source> \<destination>**: <sub><sup> Securely copy files between hosts. </sup></sub>

## Process Management

- **kill \<pid>**: <sub><sup> Terminate a process by ID. </sup></sub>
- **killall \<process_name>**: <sub><sup> Terminate a process by name. </sup></sub>
- **ps aux**: <sub><sup> Display all running processes. </sup></sub>
- **pkill \<process_name>**: <sub><sup> Send signal to terminate a process by name. </sup></sub>
- **pgrep \<process_name>**: <sub><sup> List processes by name. </sup></sub>
- **jobs**: <sub><sup> Display jobs running in the background. </sup></sub>
- **bg**: <sub><sup> Move a job to the background. </sup></sub>
- **fg**: <sub><sup> Bring a job to the foreground. </sup></sub>
- **nice \<command>**: <sub><sup> Run a command with modified scheduling priority. </sup></sub>

## System Maintenance

- **shutdown \<options>**: <sub><sup> Shut down or restart the system. </sup></sub>
- **reboot**: <sub><sup> Reboot the system. </sup></sub>
- **poweroff**: <sub><sup> Power off the system. </sup></sub>
- **tar \<options> \<archive_file> \<files_or_directories>**: <sub><sup> Create or extract tar archives. </sup></sub>
- **gzip \<file>**: <sub><sup> Compress or decompress files using gzip. </sup></sub>
- **unzip \<file. </sup></sub>zip>**: <sub><sup> Extract files from a zip archive. </sup></sub>
- **df -h**: <sub><sup> Show disk space usage in human-readable format. </sup></sub>
- **du -h**: <sub><sup> Show directory space usage in human-readable format. </sup></sub>

## File Searching and Manipulation

- **find \<path> -name \<filename>**: <sub><sup> Search for files by name. </sup></sub>
- **grep \<pattern> \<file>**: <sub><sup> Search for a pattern in a file. </sup></sub>
- **sed \<options> \<file>**: <sub><sup> Stream editor for filtering and transforming text. </sup></sub>
- **awk \<pattern> \<file>**: <sub><sup> Pattern scanning and processing language. </sup></sub>
- **sort \<file>**: <sub><sup> Sort lines of text files. </sup></sub>
- **wc \<file>**: <sub><sup> Count lines, words, and characters in a file. </sup></sub>


---

Feel free to add or modify commands based on your needs and preferences. </sup></sub>
