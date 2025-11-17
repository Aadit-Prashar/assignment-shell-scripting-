**Linux Shell Assignment**

-->📘 Project Overview
This repository contains three functional Bash scripts that demonstrate essential Linux automation tasks.

-->Each script follows good scripting practices, including:
1) Clear comments and meaningful variable names
2) Proper logging and timestamping
3) Error handling for robustness
4) These scripts were developed as part of Task 3 – Shell Script Development.

-->📂 Repository Contents
**File/Folder**     Description**	        
backup.sh	        Creates a timestamped backup of a specified directory and logs the operation.
monitoring.sh	    monitors and logs CPU and memory usage at regular intervals.
download.sh	      Downloads a file from the internet and stores it in a predefined directory.
README.md	        Project documentation and usage instructions.
/Images/	        Folder containing screenshots of the scripts being executed.


-->🚀 Script Descriptions
📦 a) Backup Script (backup.sh)
Purpose:
Creates a timestamped backup of a specified directory and logs the result.

**Usage:**

./scripts/backup.sh <target_directory>
Example:
./scripts/backup.sh /home/aadit_prashar/documents

Log Location:
/home/aadit_prashar/backup/logs/log.txt
Example:
/home/aadit_prashar/backup/logs/log.txt

💻 b) System Monitoring Script (monitoring.sh)
Purpose:
Logs the CPU and memory usage at regular intervals in a log file.

**Usage:**

./scripts/monitoring.sh
Log Location:
/home/aadit_prashar/monitoring_logs/sys_monitoring.log

Default Interval: 5 seconds
We press Ctrl + C to stop logging.

🌐 c) Automated Download Script (download.sh)
Purpose:
It downloads a file from a given URL and stores it in a predefined directory.

Usage:

./scripts/download.sh <file_url>
Example:

./scripts/download.sh https://example.com/file.zip
Download Location:
/home/aadit_prashar/downloads

Log File:
/home/aadit_prashar/downloads/download_log.txt

**Important Information**
1) Tested successfully on Ubuntu 22.04.
2) Make sure wget, curl, and top commands are installed.
3) Adjust directory paths before execution.

👨‍💻 Author
Name: Aadit Prashar
Date: 13 November 2025
Course/Task: Linux Shell Scripting Assignment – Task 3
