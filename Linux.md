# Linux Basics

## Directory Navigation

`pwd`
Used to confirm your exact location in the filesystem. Very useful inside scripts, remote servers, and deep directory structures where losing context is easy.

`ls`
Used to quickly inspect directory contents. Often combined with options to understand file types, permissions, and hidden configuration files.

`ls -l`
Used when you need detailed metadata such as permissions, ownership, file size, and timestamps. Commonly used during debugging permission issues.

`ls -a`
Used to reveal hidden files like configuration files and version control directories.

`cd directory`
Used to move between directories for navigation, project work, and script execution.

`cd ..`
Used to move upward in the directory hierarchy when navigating complex paths.

`cd ~`
Used to instantly return to the home directory from anywhere.

`/` root directory
Acts as the base of the entire Linux filesystem hierarchy.

`/home`
Stores personal directories for each user, isolating user data from system files.

## File and Directory Management

`mkdir directory`
Used to create folders for organizing files, projects, and environments.

`mkdir -p parent/child`
Used in automation and scripts to ensure directory paths exist without errors.

`touch file`
Used to create placeholder files or update file timestamps for build systems and automation tools.

`cp source destination`
Used to duplicate files or directories for backups, testing, or deployment.

`mv source destination`
Used for renaming files or reorganizing directory structures.

`rm file`
Used to permanently remove files. Often combined with caution in scripts.

`rm -r directory`
Used to remove directories and their contents. Common in cleanup operations.

`rmdir directory`
Used to remove directories only when they are empty, ensuring safe deletion.

## Viewing and Inspecting Files

`cat file`
Used to quickly inspect small files or chain outputs using pipes.

`less file`
Used for reading large files such as logs and configuration files without loading everything into memory.

`head file`
Used to preview the beginning of files, often for logs or data files.

`tail file`
Used to inspect the most recent entries in logs or files.

`tail -f file`
Used for real-time monitoring of logs during application execution.

`vim file`
Used for editing configuration files, scripts, and code directly from the terminal.

## Ownership and Permissions

`ls -l`
Used to verify who owns a file and what actions are permitted.

`chown user file`
Used by administrators to transfer file ownership.

`chown user:group file`
Used when managing collaborative access across users and groups.

`chmod mode file`
Used to control read, write, and execute permissions for security and execution control.

## Search and File Utilities

`find path -name name`
Used to locate files across large directory trees.

`grep pattern file`
Used to search text inside files, logs, and command outputs.

`wc file`
Used to measure file size in terms of lines, words, and characters.

`sort file`
Used to organize text data alphabetically or numerically.

## System Monitoring and Resource Usage

`top`
Used to monitor CPU, memory usage, and running processes in real time.

`ps aux`
Used to inspect currently running processes and diagnose issues.

`df -h`
Used to check disk usage and prevent storage exhaustion.

`du -sh directory`
Used to identify directories consuming the most disk space.

`free -m`
Used to analyze memory usage and availability.

`uptime`
Used to assess system stability and load over time.

## Documentation and Help

`man command`
Used to read official documentation for commands.

`command --help`
Used for quick reference to command options.

`history`
Used to review previously executed commands.

`clear`
Used to clean the terminal view for readability.
