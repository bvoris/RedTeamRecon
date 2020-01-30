# RedTeamRecon
Red Team Reconnaissance Tool for Windows systems

Red Team Recon is a red team tool to be run on Windows Systems for reonnaissance gathering

This tool will require escalated privileges

To be used for demonstration purposes only

How to use RedTeamRecon

Download the recon.txt file to the local machine

Rename the file to recon.bat and run with escalated privilege command prompt

If file cannot be loaded as a batch file:

Open a Command Prompt

Go to the file location

type cmd < recon.txt 

Once the file has been executed a new file will be created at c:\TMP\systemdata.cfg with detailed host information.

c:\TMP\systemdata.cfg will contain the following information:

Hostname, OS information, BIOS, physical hardware, recent hotfixes, local users and groups, local privilege information, complete network information (interfaces, IP v4/v6 stack, routes, active connections) WiFi profiles (profile name, SSID, Connection, Encryption, Pre-Shared Keys), Current running Processes, writable directory information, any locally stored clear-text credential strings.

Special thanks to 0xsp for syntax and recommended commandlines for reconnaissance
