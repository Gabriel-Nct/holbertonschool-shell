# Shell Basics - README

## Project Overview

This project covers fundamental shell commands and concepts. The tasks involve creating scripts to perform various tasks such as navigating the filesystem, manipulating files, and understanding shell commands.

### Commands Overview

The following commands are explored:

-   `cd`
-   `ls`
-   `pwd`
-   `less`
-   `file`
-   `ln`
-   `cp`
-   `mv`
-   `rm`
-   `mkdir`
-   `type`
-   `which`
-   `help`
-   `man`

### Learning Objectives

By the end of this project, you are expected to understand and explain the following:

#### General

-   What does RTFM mean?
-   What is a Shebang (`#!/bin/bash`)?

#### What is the Shell

-   What is a shell?
-   Difference between a terminal and a shell.
-   Shell prompt usage.
-   Using history (the basics).

#### Navigation

-   What do the commands or built-ins `cd`, `pwd`, `ls` do?
-   Navigating the filesystem.
-   Understanding the `.`, `..` directories.
-   Working directory, printing it, and how to change it.
-   Understanding the root directory and the home directory.
-   Difference between the root directory and the home directory of the user `root`.
-   Characteristics of hidden files and how to list them.
-   What does the command `cd -` do?

#### Looking Around

-   What do the commands `ls`, `less`, `file` do?
-   Using options and arguments with commands.
-   Understanding `ls` long format and how to display it.
-   Guided tour of files.
-   What does the `ln` command do?
-   Important directories and symbolic/hard links.

#### Manipulating Files

-   Commands `cp`, `mv`, `rm`, `mkdir`.
-   What are wildcards and how to use them.

#### Working with Commands

-   Commands `type`, `which`, `help`, `man`.
-   Different types of commands.
-   What is an alias?
-   When to use `help` instead of `man`.

#### Reading Man Pages

-   How to read a man page.
-   Sections of man pages.
    -   User commands.
    -   System calls.
    -   Library functions.

#### Keyboard Shortcuts for Bash

-   Common shortcuts for Bash.

#### LTS

-   What does LTS mean?

### Requirements

-   Allowed editors: `vi`, `vim`, `emacs`.
-   All scripts tested on Ubuntu 22.04 LTS.
-   Each script should be exactly two lines long (`wc -l file` should print 2).
-   Files should end with a new line.
-   First line of all files must be `#!/bin/bash`.
-   A `README.md` file at the root of the repository with a description.
-   A `README.md` file at the project folder describing what each script does.
-   No use of backticks, `&&`, `||`, or `;`.
-   Scripts must be executable (`chmod u+x file`).

### Example Usage

Here’s how to create and run a simple script:

1.  **Create a Script**:
```bash
$ echo '#!/bin/bash' > script.sh
$ echo 'ls' >> script.sh
```

2. **Make the Script Executable**:
```bash
$ chmod u+x script.sh
```

3. **Run the Script**:
```bash
$ ./script.sh
```
