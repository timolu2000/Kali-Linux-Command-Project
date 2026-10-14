# Kali Linux Command Line and File Management Project

This project demonstrates the practical use of **Kali Linux command-line tools** for navigating the Linux file system, creating and managing directories and files, editing text, and updating system packages. The project provides hands-on experience with fundamental Linux terminal commands and basic system administration tasks. GRC ASSIGNMENT

## Table of Contents
- Project Overview
- Network Topology
- Tools and Technologies
- Configuration Steps
- Results and Findings
- Author

## Project Overview

The purpose of this project was to develop practical experience using the **Kali Linux terminal** and understand how common Linux commands are used to interact with the operating system.

The project covered accessing Linux manual pages, navigating directories, viewing directory contents, creating and removing directories, creating and editing text files, moving files, and updating the Kali Linux package repository.

## Network Topology

This project focused primarily on **Linux command-line and file-system administration** rather than the configuration of a network topology.

The environment consisted of:

- **Kali Linux** operating system
- Kali Linux terminal
- Local Linux file system
- User home directory: `/home/kali`
- `Desktop` directory
- `Documents` directory
- Kali Linux package repositories

No routers, switches, network addressing scheme, or multi-device network topology was configured as part of the documented tasks.

## Tools and Technologies

- **Kali Linux**
- **Linux Terminal**
- Linux manual pages
- **GNU Nano**
- Linux file system
- Advanced Package Tool (**APT**)
- `man`
- `pwd`
- `ls`
- `ls -l`
- `cd`
- `mkdir`
- `rmdir`
- `touch`
- `echo`
- `cat`
- `rm`
- `mv`
- `nano`
- `apt update`
- `sudo apt update`

## Configuration Steps

1. Opened the **Kali Linux terminal** and accessed the Linux manual system using the `man` command. GRC ASSIGNMENT

2. Used `man pwd` to access the manual page for the `pwd` command and review its purpose and available options.

3. Executed `pwd` to display the current working directory, which returned `/home/kali`. GRC ASSIGNMENT

4. Used `ls` to display files and directories within the current location.

5. Used `cd Desktop` to navigate from the home directory into the **Desktop** directory and used `cd ..` to move back to the parent directory. GRC ASSIGNMENT

6. Executed `ls -l` to display a detailed listing of files and directories, including permissions, ownership, size, and modification information. GRC ASSIGNMENT

7. Created a new directory named `yemi` using `mkdir yemi` and confirmed its creation using `ls`.

8. Removed the directory using `rmdir yemi` and verified that it was successfully deleted. GRC ASSIGNMENT

9. Created a new text file named `ope.txt` using `touch ope.txt`.

10. Added text to the file using `echo 'This is my life' > ope.txt` and displayed its contents using `cat ope.txt`.

11. Appended additional text using `echo 'This is mine' >> ope.txt` and verified the updated contents with `cat ope.txt`. GRC ASSIGNMENT

12. Used `rm ope.txt` to remove the text file and confirmed its deletion using `ls`.

13. Recreated `ope.txt` and moved it into the **Documents** directory using `mv ope.txt Documents`.

14. Navigated into the Documents directory using `cd Documents` and verified that `ope.txt` had been moved successfully. GRC ASSIGNMENT

15. Used `nano ope.txt` to open and modify the file using the **GNU Nano text editor**. GRC ASSIGNMENT

16. Attempted to update the Kali Linux package repository using `apt update`. The command returned permission-related errors because it required elevated privileges.

17. Corrected the permission issue by running `sudo apt update` and authenticated with the Kali user password.

18. Successfully downloaded updated package information from the Kali Linux repositories. The update reported that **1,404 packages could be upgraded**. GRC ASSIGNMENT

## Results and Findings

The project successfully demonstrated practical use of fundamental **Linux command-line operations** within Kali Linux.

- Successfully navigated the Linux file system using `pwd`, `cd`, and `ls`.
- Used `man` to access Linux command documentation.
- Created and removed directories using `mkdir` and `rmdir`.
- Created files using `touch`.
- Wrote and appended text using `echo`, `>` and `>>`.
- Displayed file contents using `cat`.
- Removed files using `rm`.
- Moved files between directories using `mv`.
- Edited a text file using **GNU Nano**.
- Identified that `apt update` requires elevated privileges when executed by a standard user.
- Successfully used `sudo apt update` to update the Kali Linux package repository.
- Developed practical familiarity with **Linux file management, command-line navigation, permissions, text editing, and basic package administration**. GRC ASSIGNMENT

## Author

**Michael Olusola-Esan**

- **Field:** Governance, Risk and Compliance (GRC)
- **Location:** London, England
- **GitHub:** [Add GitHub Profile]
- **LinkedIn:** [Add LinkedIn Profile]
- **Email:** [Add Professional Email]
