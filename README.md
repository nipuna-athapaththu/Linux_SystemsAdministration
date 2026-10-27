\# USJP Systems Administration Labs (IIN 3462)



This repository contains practical Linux and Shell Scripting laboratory tasks completed as part of my BICT Networking specialized degree at the Faculty of Technology, University of Sri Jayewardenepura.



\---



\## 🐧 Lab Overviews \& Implementation Details



\### Lab 01: Introduction to Linux

\- \*\*Objective:\*\* Get familiar with the Linux terminal environment, basic file system navigation, listing attributes, and the `vi` text editor\[cite: 21, 33].

\- \*\*Key Tasks:\*\* 

&#x20; \* Inspected system date, logged-in users (`who`), and current directory (`pwd`)\[cite: 21].

&#x20; \* Explored the root file system partition structure using `ls -asl`\[cite: 21].

&#x20; \* Created user directories and practiced file creation/editing using the `vi` editor (`myinfor.txt`)\[cite: 21].



\### Lab 02: Linux Essentials (Inodes, Links \& Permissions)

\- \*\*Objective:\*\* Understand Linux file system internals, symbolic/hard links, file permissions, and standard output redirection\[cite: 23, 24, 25].

\- \*\*Key Tasks:\*\*

&#x20; \* Examined file `inode` numbers using `ls -il`\[cite: 23].

&#x20; \* Created symbolic (soft) links and hard links, testing file behavior when original files are modified or deleted\[cite: 23, 24].

&#x20; \* Managed directory permissions (`chmod 777`) and redirected stdout/stderr streams (`1>`, `2>`, `1>>`)\[cite: 25].



\### Lab 03: Shell Scripting - Part 1 (Basics \& Variables)

\- \*\*Objective:\*\* Write and execute basic Bash shell scripts, handle execution permissions, utilize system variables, and perform arithmetic operations\[cite: 26, 27, 28].

\- \*\*Key Tasks:\*\*

&#x20; \* Assigned script execution permissions using `chmod +x`\[cite: 26].

&#x20; \* Experimented with quoting rules, escape characters, and built-in system variables (`BASH`, `HOME`, `USER`, `PWD`)\[cite: 27, 28].

&#x20; \* Implemented `awk` calculations and formatted date outputs using the `date` utility\[cite: 29].



\### Lab 04: Shell Scripting - Part 2 (Conditional Statements)

\- \*\*Objective:\*\* Implement conditional execution logic using `if-else` blocks and `case` statements in Bash\[cite: 31, 32].

\- \*\*Key Tasks:\*\*

&#x20; \* Handled command-line arguments validation (`$#`, `$?` exit statuses)\[cite: 31].

&#x20; \* Built scripts to evaluate positive/negative integers and compare numeric inputs\[cite: 31].

&#x20; \* Developed vehicle category charge calculators using `case` branch statements\[cite: 32].



\### Lab 05: Shell Scripting - Part 3 (Loops)

\- \*\*Objective:\*\* Automate repetitive tasks using iteration control structures (`for` and `while` loops)\[cite: 19].

\- \*\*Key Tasks:\*\*

&#x20; \* Created multiplication table scripts utilizing `for` loops and command-line inputs\[cite: 19].

&#x20; \* Rewrote iteration logic using `while` loop syntax\[cite: 19].



\---



\## 🧰 Tools \& Technologies Used

\- \*\*OS:\*\* Kali Linux / Ubuntu Server

\- \*\*Shell:\*\* Bash (Bourne Again SHell)

\- \*\*Utilities:\*\* `vi` Editor, `awk`, `expr`, `ln`, `chmod`, `ls`

