kWatch
======

- Backup systems need an efficient method to find the latest modified files. They either use Depth First Search (DFS) or costly per-file data structures

- Our system eliminates DFS and takes 92% lesser memory compared to Inotify (currently used in Linux 3.2)

- Our system consists of a Loadable Kernel Module (LKM) to track modified files and a user level program to track/untrack directories

- Used C, LKM programming, kernel debugging