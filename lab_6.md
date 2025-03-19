# Experiment 10:  
Create the operator1 user and confirm that it exists in the
system. Set the password for operator1. Create the
additional operator2 and operator3 users. Set their
passwords as well. Run the usermod -c command to update
the comments of the operator1 user account. Remove
the operator3 user from the system.

## Description  
In this experiment, we create multiple user accounts, set their passwords, update user information, and delete a user account. The steps performed include:

- **Creating users:** `operator1`, `operator2`, and `operator3` using the `useradd` command.
- **Setting passwords:** Assigning passwords to each user with the `passwd` command.
- **Updating user details:** Using `usermod -c` to modify the comment field for `operator1`.
- **Removing a user:** Deleting `operator3` using `userdel -r`.

These commands help in managing user accounts in a Linux system.

## Screenshot  
![exp6](https://github.com/user-attachments/assets/22699869-f475-4811-a4dc-a04a8d2c378e)


## Commands Used  
```bash
sudo useradd operator1
sudo passwd operator1
sudo useradd operator2
sudo passwd operator2
sudo useradd operator3
sudo passwd operator3
sudo usermod -c "Primary system operator" operator1
sudo userdel -r operator3
