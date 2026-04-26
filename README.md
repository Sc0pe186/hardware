IT Admin Tool
Description
IT Admin Tool is a terminal-based Python project created for aspiring IT system integration specialists. It provides practical administrative functions such as system monitoring, network inspection, connectivity testing, and report logging in a structured and understandable way.

The goal of this project is to demonstrate clean Python coding, safe command handling, and a basic understanding of typical day-to-day administration tasks in a professional environment.

Features
Display system information:
CPU usage
RAM usage
Disk usage
Run network analysis:
IP configuration
ARP table
Test internet connectivity with ping
Save generated results to timestamped report files
Write application events to a log file
Menu-based terminal interface with input validation and error handling
Technologies
Python 3
Standard library modules:
subprocess
logging
platform
pathlib
socket
datetime
shutil
os
Usage
Install Python 3.
Install dependencies:
pip install -r requirements.txt
Start the application:
python main.py
Use the menu to choose an action.
Project Purpose
This project was designed as a portfolio example for a motivated beginner with a serious interest in system integration. It focuses on practical usefulness, stable behavior, and clean structure instead of unnecessary complexity.

It is suitable for:

job applications
technical interviews
learning basic Python project organization
demonstrating an understanding of system administration tasks
Notes
On Windows, the tool uses ipconfig, arp, and ping.
For hardware information on Windows, it uses safe PowerShell CIM queries.
On Linux-based systems, it attempts to use equivalent commands where possible.
Reports are saved in the reports folder.
Application logs are stored in the logs folder.
