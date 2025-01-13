
# Shell Permissions Project

This project includes a series of shell scripts to manage Linux file permissions and user/group management using various commands. It covers tasks such as changing file owners, adding execute permissions, and manipulating file modes.

## Learning Objectives

At the end of this project, you should be able to:

-   Explain the purpose and usage of the following commands:
    -   `chmod`
    -   `sudo`
    -   `su`
    -   `chown`
    -   `chgrp`
    -   `id`
    -   `groups`
    -   `whoami`
    -   `adduser`
    -   `useradd`
    -   `addgroup`
-   Understand Linux file permissions.
-   Represent each of the three sets of permissions (owner, group, and other) as a single digit.
-   Change permissions, owner, and group of files.
-   Understand why a normal user cannot change the owner of a file.
-   Run commands with root privileges.
-   Change the user ID or become a superuser.

## Scripts

1.  **0-iam_betty**: Switch the current user to the user "betty".
2.  **1-who_am_i**: Print the effective username of the current user.
3.  **2-groups**: Print all the groups the current user is part of.
4.  **3-new_owner**: Change the owner of the file `hello` to the user "betty".
5.  **4-empty**: Create an empty file called `hello`.
6.  **5-execute**: Add execute permission to the owner of the file `hello`.
7.  **6-multiple_permissions**: Add execute permission to the owner and group owner, and read permission to other users for the file `hello`.
8.  **7-everybody**: Add execute permission to the owner, the group owner, and other users for the file `hello`.
9.  **8-James_Bond**: Set the permission of the file `hello` so that the owner and group have no permissions, and others have all permissions.
10.  **9-John_Doe**: Set the mode of the file `hello` to `rwxr-x-wx`.
11.  **10-mirror_permissions**: Set the mode of the file `hello` to match that of the file `olleh`.
12.  **11-directories_permissions**: Add execute permission to all subdirectories of the current directory for the owner, group owner, and all other users.

## Requirements

-   All scripts are to be tested on Ubuntu 22.04 LTS.
-   All files should be exactly two lines long (`$ wc -l file` should print 2).
-   All scripts must be executable.
-   You are not allowed to use backticks, `&&`, `||`, or `;` in your scripts.
-   All files must end with a new line.
-   The first line of all scripts should be `#!/bin/bash`.
-   A `README.md` file is mandatory and must describe the functionality of the scripts.
