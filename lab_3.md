# Experiment 3:  
Use Vim,nano, to edit the editing_final_lab.txt file. Use the
lab_file shell variable. Enter the visual mode of Vim. Remove
the last seven characters from the first column on the first
line. Preserve only the first four characters of the first
column. 

## Description  
In this experiment, we create and edit a file using both the Nano and Vim text editors. The steps performed include:  

- **Creating a file:** Using the `touch` command and storing the filename in a shell variable.  
- **Editing with Nano:** Writing sample text and saving the file.  
- **Editing with Vim:** Using visual mode to remove specific characters.  
- **Using Visual Mode in Vim:**  
  - Removing the last seven characters of the first line.  
  - Keeping only the first four characters of the first line.  

These commands demonstrate basic text editing in Linux using different editors.  

## Screenshot  
![Screenshot 2025-03-19 111010](https://github.com/user-attachments/assets/5ffef626-54dd-459b-9718-cf571e51ea36)
![Screenshot 2025-03-19 110922](https://github.com/user-attachments/assets/04fa5d58-75b0-4116-a749-19519419ac11)


## Commands Used  
```bash
myfile="lab_notes.txt"   # Define an easy variable name  
touch $myfile            # Create an empty file  
nano $myfile             # Open file in Nano  
vim $myfile              # Open file in Vim  
V                        # Enter visual mode (line mode)  
Ctrl + V                 # Enter visual block mode  
d                        # Delete selected text  
:wq                      # Save and exit Vim  
