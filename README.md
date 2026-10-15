# windows-command-line-notes
My notes from the TryHackMe Windows Command Line room.
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
