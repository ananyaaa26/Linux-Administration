# Experiment 1:  
Use the touch command to create sets of empty practice files.  
Create six files with names of the form `songX.mp3`, `snapX.jpg`, and `filmX.avi`.  
Create three subdirectories for organizing files: `friends`, `family`, and `work`.  
Use a single command to create all three subdirectories at the same time.  

## Description  
In this experiment, we use the `touch` command to create multiple empty files at once,  
and the `mkdir` command to create multiple directories in a single command.  

- **File Creation:** We create six files for each category:  
  - `songX.mp3` (e.g., `song1.mp3` to `song6.mp3`)  
  - `snapX.jpg` (e.g., `snap1.jpg` to `snap6.jpg`)  
  - `filmX.avi` (e.g., `film1.avi` to `film6.avi`)  

- **Directory Creation:** We organize files into three directories:  
  - `friends`  
  - `family`  
  - `work`  

- **Execution:** The files and directories are created in the `classwork` directory,  
  ensuring proper organization.  

## Screenshot  
![Screenshot 2025-03-19 102258](https://github.com/user-attachments/assets/35e46687-a70b-4493-847f-14cd2096f753)
 

## Commands Used  
```bash
cd Desktop
cd classwork
touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi
mkdir friends family work
ls
