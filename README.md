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
