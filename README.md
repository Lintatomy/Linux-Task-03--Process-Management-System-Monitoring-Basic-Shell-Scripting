# Linux-Task-03--Process-Management-System-Monitoring-Basic-Shell-Scripting

Objective
The purpose of this task is to understand how Linux manages processes, monitors system resources,
and automates tasks using shell scripts.
These are essential skills for Linux Administrators, SOC Analysts, and Cyber Security Professionals.

Part A: Process Monitoring :-

ps
ps aux
top
htop

Observations
- Learned how to view running processes.
- Identified Process IDs (PIDs).
- Monitored CPU and memory usage.
- Observed active system processes.

Screenshots
<img width="1383" height="1137" alt="shot1" src="https://github.com/user-attachments/assets/07ceb789-85df-474d-9094-d2a5474dab59" />

<img width="1203" height="1308" alt="shot1 1" src="https://github.com/user-attachments/assets/5abfebc6-0baa-481a-9e6b-d386918bd48e" />


<img width="1402" height="1122" alt="shot1 2" src="https://github.com/user-attachments/assets/41223b6a-2cea-4c83-b0e4-f69d4c7224de" />



Part B – Process Management :-

sleep 300
ps aux | grep sleep
kill PID
kill -9 PID

Activities 
- Created a temporary process using sleep.
- Located the process PID.
- Terminated the process using kill.
- Forcefully terminated the process using kill -9.

  Screenshot
  <img width="1666" height="944" alt="shot2" src="https://github.com/user-attachments/assets/26554605-69c9-41ff-b9c2-ec4e77ec74c6" />

<img width="2120" height="742" alt="shot2 1" src="https://github.com/user-attachments/assets/f089a249-5d18-4d1c-8c0b-6ceabf392497" />

<img width="2024" height="777" alt="shot2 2" src="https://github.com/user-attachments/assets/462fd3d9-9702-4847-ae08-8d07cb15c745" />



Part C – System Monitoring :-

Commands 
free -h
df -h
uptime
uname -a

Informations
- Total RAM
- Available RAM
- Disk Usage
- System Uptime
- Kernel Version

Files 
command output.txt
system summary.txt

Screenshot
<img width="1958" height="803" alt="shot3" src="https://github.com/user-attachments/assets/04272968-5a97-43b7-be9a-74ee01427c90" />



Part D – Service Monitoring :-

Commands
systemctl status ssh
systemctl status NetworkManager

Observation
- Verified service status.
- Checked whether services were active and running.
- Learned the importance of background services.

  Screenshot
  <img width="996" height="1578" alt="shot4" src="https://github.com/user-attachments/assets/76dd7e58-8846-4d0f-ba4d-d4c2e92f9a94" />

<img width="1897" height="829" alt="shot4 1" src="https://github.com/user-attachments/assets/0c5d2697-415a-4b18-949f-7fb14add73de" />



Part E – Shell Scripting :-

Script
system report.sh

Commands 
chmod +x system_report.sh
./system_report.sh

The script displays:
- Current User
- Hostname
- Date & Time
- Current Directory
- Memory Usage
- Disk Usage
- System Uptime
- Kernel Version

Screenshots
<img width="1466" height="1073" alt="shot5" src="https://github.com/user-attachments/assets/94d966b9-c539-4084-99b0-b7e864b892b9" />



Part F – Security Monitoring Challenge :-

Commands 
netstat
ss
who
w
last

Files 
System summary.txt

Screenshort
<img width="1744" height="901" alt="shot6" src="https://github.com/user-attachments/assets/c6c9059e-eae7-4f07-abea-ed739e9e4346" />



Part G – Mini SOC Activity :-

Learned 
1. How would you determine the resource-intensive processes?
To monitor CPU and memory usage. Resource-intensive processes will be flagged for further analysis.

2. How would you determine whether the process is suspicious?
Check the process name.
Check the process id (PID).
Determine the user who initiated the process.
Check CPU and memory usage.
Determine the process file location.
Check whether it belongs to any legitimate application process.

3. What would you do before killing a process?
Before killing a process, the following information will be collected:
 Process name
 PID
 User initiating the process
 CPU usage
 Memory usage
 PPID
 File Location
 Network connections



Linux Task 03_linta/

├── Screenshots/
├── system report.sh
├── command output.txt
├── system summary.txt
└── README.md
