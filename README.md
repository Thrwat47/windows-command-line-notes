# TryHackMe — Windows Command Line

**Completed:** 10/15/2026

## Overview
In this room I learned the essential Windows commands used to check system information, troubleshoot networks, manage files and disks, and control processes from the command line.

## Commands Covered

### Basic System Information
- `ver` — show the Windows version
- `systeminfo` — detailed system and OS information
- `hostname` — show the computer name

### Network Troubleshooting
- `ipconfig /all` — network adapter details
- `ping` — test connectivity to a host
- `tracert` — trace the route to a host
- `nslookup` — DNS lookup
- `netstat -ano` — active connections and listening ports

### File and Disk Management
- `dir` — list files and folders
- `cd` — change directory
- `type` — display file content
- `tree` — show folder structure

### Task and Process Management
- `tasklist` — list running processes
- `taskkill /PID <id> /F` — stop a process

## What I Learned
- I can collect basic system information quickly with `systeminfo` and `hostname` without using the GUI.
- `ipconfig`, `ping`, `tracert`, and `nslookup` help me find where a network problem is: the adapter, the connection, the route, or DNS.
- `netstat -ano` shows active connections with their process IDs, which is useful for spotting suspicious connections.
- I can match a process ID from `netstat` with `tasklist` to find which program is making a connection.
- The command line is faster than the GUI for troubleshooting, and it is also very useful in SOC work and IT help desk work.

## Screenshot
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/8661633e-f0c6-444f-a444-71de6083406e" /><img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/f9b5348b-f48f-4205-9d03-4d6596d4e18f" /><img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/ccb74c97-e1c6-468b-afad-edc93c203927" /><img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/c04e4d84-a233-461b-9360-18ebd44d5c84" /><img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/ce9e7b2d-8388-4381-9988-f6de7e76c2fc" /><img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/eb637056-dc7d-4a0b-b91a-59c2fdd15d92" />





