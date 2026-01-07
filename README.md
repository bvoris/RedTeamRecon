# RedTeamRecon
Created by: Brad Voris<BR />
Red Team Reconnaissance Tool for Windows systems

Red Team Recon is a red team tool to be run on Windows Systems for reconnaissance gathering

This tool will require escalated privileges

To be used for demonstration purposes only

RedTeamRecon will gather the following information:

Hostname, OS information, BIOS, physical hardware, recent hotfixes, local users and groups, local privilege information, complete network information (interfaces, IP v4/v6 stack, routes, active connections) WiFi profiles (profile name, SSID, Connection, Encryption, Pre-Shared Keys), Current running Processes, writable directory information, local firewall profiles, local share information, any locally stored clear-text credential strings.

***Updated 1/25/2022 with cmdkey /savecred /list /pass

How to use RedTeamRecon

Download the recon.txt file to the local machine

Rename the file to recon.bat and run with escalated privilege command prompt

If file cannot be loaded as a batch file:

Open a Command Prompt

Go to the file location

type cmd < recon.txt 

Once the file has been executed a new file will be created at c:\TMP\systemdata.cfg with detailed host information.

c:\TMP\systemdata.cfg will contain the all of the information from the recon.

Special thanks to 0xsp & Morph3Sec for syntax and recommended commandlines for reconnaissance
https://0xsp.com/offensive/red-ops-techniques/red-team-cheatsheet

## Connect with me at

<a href="https://twitter.com/HMInfoSecViking?ref_src=twsrc%5Etfw"><IMG SRC="https://github.com/bvoris/bvoris/blob/master/twitter.jpg" WIDTH=10% HEIGHT=10% ALIGN=LEFT></a>	
<a href="https://www.linkedin.com/in/brad-voris" target="_blank"><IMG SRC="https://github.com/bvoris/bvoris/blob/master/linkedin.png" WIDTH=10% HEIGHT=4% ALIGN=RIGHT></a>
<BR /> 
<A HREF="https://www.victimoftechnology.com">Victim Of Technology<A />
<BR /><BR />

