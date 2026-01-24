
# Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, **without the help of Google**:

## General

* What happens when you type:

  ```bash
  ls -l *.txt
  ```

## Shell Initialization Files

* What are the `/etc/profile` file and the `/etc/profile.d` directory
* What is the `~/.bashrc` file

## Variables

* What is the difference between a local and a global variable
* What is a reserved variable
* How to create, update, and delete shell variables
* What are the roles of the following reserved variables:

  * `HOME`
  * `PATH`
  * `PS1`
* What are special parameters
* What is the special parameter `$?`

## Expansions

* What is expansion and how to use it
* What is the difference between single and double quotes and how to use them properly
* How to do command substitution with `$()` and backticks

## Shell Arithmetic

* How to perform arithmetic operations with the shell

## The `alias` Command

* How to create an alias
* How to list aliases
* How to temporarily disable an alias

## Other Help Pages

* How to execute commands from a file in the current shell

---

# Requirements

## General

* Allowed editors:

  * `vi`
  * `vim`
  * `emacs`
* All your scripts will be tested on **Ubuntu 20.04 LTS**
* All your scripts should be **exactly two lines long**

  ```bash
  wc -l file
  ```

  should print `2`
* All your files should end with a new line (why?)
* The first line of all your files should be exactly:

  ```bash
  #!/bin/bash
  ```
* A `README.md` file, at the root of the folder of the project, describing what each script is doing
* You are **not allowed** to use:

  * `&&`
  * `||`
  * `;`
* You are **not allowed** to use:

  * `bc`
  * `sed`
  * `awk`
* All your files must be executable

---

# More Info

* Read your:

  * `/etc/profile`
  * `/etc/inputrc`
  * `~/.bashrc`
* Look at some files in the `/etc/profile.d` directory.

> **Note:**
> You do not have to learn about `awk`, `tar`, `bzip2`, `date`, `scp`, `ulimit`, `umask`, or shell scripting yet.


