# Experiment 7:  
Implement `chown` and `chmod` commands with their options.  

## Description  
In this experiment, we use the `chown` command to change file ownership and  
the `chmod` command to modify file permissions.  

![Screenshot 2025-03-19 125049](https://github.com/user-attachments/assets/fae859bc-2bb3-40d8-bad3-837f3f76f1ed)
![Screenshot 2025-03-19 124840](https://github.com/user-attachments/assets/41f2b596-bb64-4200-af03-2cbe606be2c3)

# Change file ownership
sudo chown ananya file.txt          # Change owner to ananya
sudo chown ananya:class file.txt    # Change owner to ananya and group to class

# Modify file permissions
chmod 744 file.txt   # Set owner: rwx, group: r, others: r
chmod +x file.txt    # Add execute permission to all users
chmod o-w file.txt   # Remove write permission from others

# Verify file permissions
ls -l file.txt       # List file details and permissions

