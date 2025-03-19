# Experiment 5:
Implement ps, top, kill command with their options.
Installing, updating, and removing software by apt-get
command.


## Description  
We will explore process monitoring and management in Linux and practice installing,  
updating, and removing software using `apt-get`. 

![Screenshot 2025-03-19 115932](https://github.com/user-attachments/assets/10927cdf-306d-4268-825e-b25862cf6eba)
![Screenshot 2025-03-19 115921](https://github.com/user-attachments/assets/c20ee69f-51fa-4392-b480-25ee9c054d5b)
![Screenshot 2025-03-19 115912](https://github.com/user-attachments/assets/1f116a68-4c7e-41c8-9a68-6343f83593d4)
![Screenshot 2025-03-19 115900](https://github.com/user-attachments/assets/a20ec402-9af6-4ded-b907-f3ebe99539a3)
![Screenshot 2025-03-19 115847](https://github.com/user-attachments/assets/dad80219-ea89-4ae8-8a82-e6d69058ff3b)
![Screenshot 2025-03-19 115837](https://github.com/user-attachments/assets/e3af1a9c-2ba2-453c-8af4-b5bda3cda07a)
![Screenshot 2025-03-19 115827](https://github.com/user-attachments/assets/77504c63-b375-408c-bd55-fc9b314ad01e)
![Screenshot 2025-03-19 115516](https://github.com/user-attachments/assets/1a8c781a-c851-4978-9e16-b1b23adb6703)
![Screenshot 2025-03-19 115505](https://github.com/user-attachments/assets/ce0873b0-431a-4e27-a8f6-7348b85d79ec)
![Screenshot 2025-03-19 114737](https://github.com/user-attachments/assets/eec1211f-faf2-44de-9b62-7a314a7ee3a8)


### **Process Management Commands**  
- **`ps` Command (Process Status)**  
  - `ps aux` → Lists all running processes with detailed information.  
  - `ps -ef` → Displays processes with full-format listing.  
  - `ps -u <username>` → Shows processes owned by a specific user.  
  - `ps -p <PID>` → Displays details of a specific process by PID.  

- **`top` Command (Real-time Process Monitoring)**  
  - `top` → Displays real-time system processes and resource usage.  
  - `top -u <username>` → Filters processes by user.  
  - Press `M` → Sorts by memory usage.  
  - Press `P` → Sorts by CPU usage.  

- **`kill` Command (Terminate Processes)**  
  - `kill <PID>` → Terminates a process by its PID.  
  - `kill -9 <PID>` → Forcefully terminates a process.  
  - `pkill <process_name>` → Kills all processes matching a given name.  
  - `killall <process_name>` → Kills all instances of a process.  

---

### **Updating and Upgrading Packages**  
- **Update package list:**  
  ```bash
  sudo apt-get update
  
