# Shell, Init Files, Variables and Expansions

## Description

This project aims to help you understand key aspects of shell scripting, including working with shell initialization files, variables, expansions, and arithmetic. By the end of this project, you should have a solid understanding of how to manage shell environments, variables, and the use of expansions in various situations.

### Learning Objectives

At the end of this project, you should be able to:

#### General Knowledge:
- Explain what happens when you run `$ ls -l *.txt`.

#### Shell Initialization Files:
- Understand the role of the `/etc/profile` file and the `/etc/profile.d` directory.
- Understand the purpose of the `~/.bashrc` file.

#### Variables:
- Know the difference between local and global variables.
- Understand what reserved variables are and how to create, update, and delete shell variables.
- Be familiar with the roles of reserved variables such as `HOME`, `PATH`, and `PS1`.
- Understand special parameters and the special parameter `$$`.

#### Expansions:
- Know what expansion is and how to use it.
- Understand the difference between single and double quotes and how to use them properly.
- Be able to perform command substitution using `$()` and backticks.

#### Shell Arithmetic:
- Perform arithmetic operations using the shell.

#### Alias Command:
- Create and manage aliases.
- List aliases.
- Temporarily disable an alias.

#### Other Help Pages:
- Execute commands from a file in the current shell using `source` or `.`.

## Resources

Refer to the following resources to help you learn:

- **Expansions**
- **Shell Arithmetic**
- **Variables**
- **Shell Initialization Files**
- **The alias Command**
- **Technical Writing**

For help with man pages, refer to:
- `printenv`, `set`, `unset`, `export`, `alias`, `unalias`, `.`, `source`, `printf`

## Requirements

### General Requirements:
- Allowed editors: `vi`, `vim`, `emacs`.
- All scripts will be tested on Ubuntu 20.04 LTS.
- All scripts should be exactly two lines long (`$ wc -l file` should print 2).
- All files must end with a new line.
- The first line of all your files should be `#!/bin/bash`.
- A `README.md` file is required at the root of the project, describing what each script does.
- Backticks, `&&`, `||`, or `;` are not allowed.
- You are not allowed to use `bc`, `sed`, or `awk` in your scripts.
- All files must be executable.

### Special Notes:
- Review the `/etc/profile`, `/etc/inputrc`, and `~/.bashrc` files to understand shell initialization.
- Take a look at files in the `/etc/profile.d` directory for further insights into shell initialization.

## Example Usage

Throughout this project, you will work with shell variables, perform expansions, and manage shell initialization files to set up your environment. You will also create and manage aliases, perform arithmetic operations, and understand how expansions work in the shell.

## Conclusion

This project helps you understand shell scripting fundamentals, particularly shell variables, expansions, and initialization files. These skills are essential for writing more complex shell scripts and managing shell environments effectively.
