# OS-Task-Lister-using-Kernel-Module
A project made as a part of the Operating System Course (UE20CS254) at PES University. The objective of the project was to demonstrate kernel module that lists all current tasks in a Linux system beginning from the init task 

## Installation
```
$ git clone https://github.com/yoyozaemon/OS-Task-Lister-using-Kernel-Module.git
$ cd OS-Task-Lister-using-Kernel-Module/
```

## How to use
```
$ cd src/[linear|dfs]
$ make                                  # Make module
$ insmod tasks_lister_[linear|dfs].ko   # Install module
$ dmesg                                 # Show message
$ rmmod tasks_lister_[linear|dfs]       # Remove module
$ dmesg                                 # Show message
$ dmesg -C                              # Clear message
```

