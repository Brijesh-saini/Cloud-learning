# Cloud-learning
This repository serves as a comprehensive resource for essential Git and Linux commands, designed to aid in the learning journey of cloud engineering and DevOps practices.

Table of Contents
Git Cheatsheet

Linux Cheatsheet

Vim Editor Basics

Git Cheatsheet
A collection of commands for version control and repository management.

Configuration & Initialization
Set User Info: git config --global user.name "[name]" and git config --global user.email "[email]".

Initialize Repo: git init (transforms a directory into a Git repository).

Clone Repo: git clone [url] (downloads an existing repository).

Everyday Workflow
Check Status: git status (see modified and staged files).

Stage Changes: git add [file].

Commit: git commit -m "[descriptive message]".

Branching: git branch [branch-name] to create; git checkout [branch] to switch.

Remote Repositories
Push: git push [alias] [branch] (upload local commits).

Pull: git pull (fetch and merge remote changes).

Remote Alias: git remote add [alias] [url].

Linux Cheatsheet
Essential commands for navigating and managing a Linux environment.

File & Directory Operations
List Files: ls (standard), ls -al (detailed information including permissions).

Navigation: cd .. (move up), cd ~ (home directory).

File Management: cat (view content), mv (move/rename), rm (delete).

Directories: mkdir (create) and rmdir (delete empty directory).

System & Permissions
Sudo: sudo (execute commands with root privileges).

Ownership: chown user:group filename.

System Status: df (disk space), free (RAM), and top (active processes).

User Management
Add User: sudo adduser username.

Modify Group: sudo usermod -a -G GROUPNAME USERNAME.

Vim Editor Basics
Quick reference for the Vim text editor.

Modes: Press i to enter Insert mode; press ESC to return to Command mode.

Saving & Quitting:

:w (save/write).

:q! (quit without saving).

:wq (save and quit).

Navigation: gg (top of file), G (bottom of file).

Editing: dd (delete line), u (undo).
