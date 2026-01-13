📡 Computer Network Project – Packet Tracer Implementation
📌 Project Overview

This project is a complete implementation of an enterprise-style computer network designed and simulated using Cisco Packet Tracer.
It demonstrates practical networking concepts including DHCP, DNS, HTTP/HTTPS, SMTP, VLANs, VTP, ACLs, RIP, OSPF, route redistribution, and Telnet.

The network is divided into four logical blocks, each fulfilling specific networking objectives. All configurations have been successfully implemented and verified using ping tests, service testing, and remote access validation.

⚠️ Note: This repository contains a finished project. No additional configuration is required.

🧠 Key Concepts Implemented

DHCP Server configuration

Web (HTTP/HTTPS), Mail (SMTP), and DNS services

VLANs & Inter-VLAN Routing

VTP (Server, Client, Transparent modes)

Port Security & LACP EtherChannel

Access Control Lists (ACLs)

RIP & OSPF Routing Protocols

RIP–OSPF Route Redistribution

Telnet (Remote Device Management)

🗂️ Project Structure (Blocks Summary)
🔹 Block 1 – Network Services

DHCP for automatic IP assignment

Web Server with custom index.html

DNS server (yourname.com)

SMTP Mail server (send & receive tested)

🔹 Block 2 – Switching & Security

Three switches connected using LACP EtherChannel

Port Security allowing only one device

🔹 Block 3 – VLANs & VTP

VLANs: Students, Faculty, Admin, IT

VTP:

S1 → Server

S2 → Transparent

S3 → Client

Inter-VLAN routing

Telnet access from VLAN 40

🔹 Block 4 – ACL Implementation

Router ACL:

PC-01 → Allowed

PC-02 → Denied

🔹 Routing & Connectivity

RIP on Routers R1, R2, R3

OSPF on Routers R3, R5, R6

RIP–OSPF Redistribution

End-to-end communication verified

🔹 Telnet Access

All routers accessible via Telnet from authorized systems
-----------------------------------------------------------------------------------------------------------------------
🖥️ Software Requirement
✔ Cisco Packet Tracer (Required)

This project runs only on Cisco Packet Tracer.
------------------------------------------------------------------------------------------------------------------------

⬇️ How to Download & Install Cisco Packet Tracer
Step 1: Create a Cisco Account

Open: https://www.netacad.com

Click Sign Up

Create a free Cisco Networking Academy account

Step 2: Download Packet Tracer

Log in to NetAcad

Go to Resources → Download Packet Tracer

Download the version for your OS:

Windows

Linux

macOS

Step 3: Install

Run the installer

Launch Packet Tracer

Log in using your NetAcad credentials
--------------------------------------------------------------------------------------------------------------
▶️ How to Run This Project (If Cisco Packet Tracer Is Already Installed)

This section is for users who already have Cisco Packet Tracer installed and want to run this project from GitHub.  <----------------------

Step 1: Download the Project from GitHub

Open this repository on GitHub

Click the green Code button

Select Download ZIP

After download, extract (unzip) the folder on your computer

📌 Make sure the folder contains a file with .pkt extension
(example: CN_PROJECT.pkt)

Step 2: Open Cisco Packet Tracer

Open Cisco Packet Tracer

Wait until the main screen loads completely

Make sure no other project is open (optional but recommended)

Step 3: Open the Project File

In Cisco Packet Tracer, click File → Open

Go to the folder where you extracted the GitHub project

Select the CN_PROJECT.pkt file

Click Open

⏳ Wait a few seconds while Packet Tracer loads all devices.

Step 4: Let the Network Stabilize (Important)

After opening the project:

Do not click anything immediately

Wait 30–60 seconds

Let all routers, switches, and PCs turn green

This allows:

Routing protocols (RIP & OSPF) to converge

Services (DHCP, DNS, SMTP, HTTP) to start properly

Step 5: Test the Project (Basic Checks)
✅ Ping Test

Click on any PC

Go to Desktop → Command Prompt

Type:

ping <destination-ip>


You should see Reply from…

✅ Web Server Test

Click on any PC in Block 1

Go to Desktop → Web Browser

Enter the configured domain (example):

http://abdulbasit.com


The webpage should load successfully

✅ Email (SMTP) Test

Click on a PC

Open Desktop → Email

Use the configured email account

Send and receive a test email

✅ Telnet Test

Click on a PC

Open Command Prompt

Type:

telnet <router-ip>


Login should be successful (for allowed systems)















--------------------------------------------------------------------------------------------------------------
👤 Author

Abdul Basit
BS Artificial Intelligence
ITU Lahore

⭐ Final Note

This repository is intended for learning, demonstration, and academic reference.
All configurations are complete, verified, and ready for review.




















