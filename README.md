# USJP Systems Administration Labs (IIN 3462)

This repository contains practical Linux and Shell Scripting laboratory tasks completed as part of my BICT Networking specialized degree at the Faculty of Technology, University of Sri Jayewardenepura.

---

## 🐧 Lab Overviews & Implementation Details

### Lab 01: Introduction to Linux
- **Objective:** Get familiar with the Linux terminal environment, basic file system navigation, listing attributes, and the `vi` text editor.
- **Key Tasks:** 
  * Inspected system date, logged-in users (`who`), and current directory (`pwd`).
  * Explored the root file system partition structure using `ls -asl`.
  * Created user directories and practiced file creation/editing using the `vi` editor (`myinfor.txt`).

### Lab 02: Linux Essentials (Inodes, Links & Permissions)
- **Objective:** Understand Linux file system internals, symbolic/hard links, file permissions, and standard output redirection.
- **Key Tasks:**
  * Examined file `inode` numbers using `ls -il`.
  * Created symbolic (soft) links and hard links, testing file behavior when original files are modified or deleted.
  * Managed directory permissions (`chmod 777`) and redirected stdout/stderr streams (`1>`, `2>`, `1>>`).

### Lab 03: Shell Scripting - Part 1 (Basics & Variables)
- **Objective:** Write and execute basic Bash shell scripts, handle execution permissions, utilize system variables, and perform arithmetic operations.
- **Key Tasks:**
  * Assigned script execution permissions using `chmod +x`.
  * Experimented with quoting rules, escape characters, and built-in system variables (`BASH`, `HOME`, `USER`, `PWD`).
  * Implemented `awk` calculations and formatted date outputs using the `date` utility.

### Lab 04: Shell Scripting - Part 2 (Conditional Statements)
- **Objective:** Implement conditional execution logic using `if-else` blocks and `case` statements in Bash.
- **Key Tasks:**
  * Handled command-line arguments validation (`$#`, `$?` exit statuses).
  * Built scripts to evaluate positive/negative integers and compare numeric inputs.
  * Developed vehicle category charge calculators using `case` branch statements.

### Lab 05: Shell Scripting - Part 3 (Loops)
- **Objective:** Automate repetitive tasks using iteration control structures (`for` and `while` loops).
- **Key Tasks:**
  * Created multiplication table scripts utilizing `for` loops and command-line inputs.
  * Rewrote iteration logic using `while` loop syntax.

---

## 🧰 Tools & Technologies Used
- **OS:** Kali Linux / Ubuntu Server
- **Shell:** Bash (Bourne Again SHell)
- **Utilities:** `vi` Editor, `awk`, `expr`, `ln`, `chmod`, `ls`
