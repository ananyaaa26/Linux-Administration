# Experiment 4
Create the /home/consultants directory.
Add write permission to the consultants group. Use the
symbolic method for setting the appropriate permissions.
Forbid others from accessing files in
the /home/consultants directory. Use the octal method for
setting the appropriate permissions.
Change the default umask for the operator1 user. The new
umask prohibits all access for users that are not in their
group. Confirm that the umask is changed.

## Description  
In this experiment, we create a secure directory for a group, modify its permissions,  
and set a restrictive default umask for a specific user.  

![Screenshot 2025-03-19 202158](https://github.com/user-attachments/assets/8eac0e04-1081-4171-aaf5-804f47e86661)
![Screenshot 2025-03-19 202037](https://github.com/user-attachments/assets/b34bcc5b-6b92-4c75-b0d5-74831c46827a)


## Commands Used  
```bash
sudo mkdir -p /home/consultants
sudo groupadd consultants
sudo chown :consultants /home/consultants
sudo chmod g+w /home/consultants
sudo chmod 770 /home/consultants
sudo useradd -m -s /bin/bash operator1
sudo nano /home/operator1/.bashrc  # Add "umask 007" at the end
sudo su - operator1
umask

