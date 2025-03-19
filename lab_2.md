# Experiment 2:  
View the gedit man page.
Use the man -k ext4 command to find the command to tune
ext4 file-system parameters.
Brace expansion is used to generate discretionary strings of
characters. Braces contain a comma-separated list of strings,
or a sequence expression. The result includes the text that
precedes or follows the brace definition.


## Description  
In this experiment, we explore three different Linux command-line functionalities:  

1. **Viewing the `gedit` man page:**  
   - The `man` command is used to view the manual page for `gedit`, a graphical text editor in Linux.

2. **Finding the command to tune ext4 file-system parameters:**  
   - The `man -k ext4` command searches for manual pages related to `ext4`.  
   - This helps identify the command used to modify ext4 file system parameters.

3. **Using Brace Expansion:**  
   - Brace expansion `{}` allows generating multiple strings efficiently.  
   - It can be used with comma-separated lists (`{a,b,c}`) or sequences (`{1..5}`).  

## Screenshot  
![Screenshot 2025-03-19 103433](https://github.com/user-attachments/assets/81dba0ed-85c4-4dad-80c1-4f216c4a55e5)


## Commands Used  
```bash
man gedit
man -k ext4
echo file{1..5}.txt
echo backup_{A,B,C}.tar.gz
mkdir project_{alpha,beta,gamma}

