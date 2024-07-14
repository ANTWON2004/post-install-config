<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objective</h2>
Assigning roles to team members and configuring the platform are essential steps to ensure its proper functionality.
<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After completing the installation, the next steps involve configuring roles, departments, teams, and user settings for optimal functionality. Navigate to the Admin Panel, specifically under Agents, to set up roles such as Supreme Admin. Additionally, configure departments like System Administrators and define teams such as Level I and Level II Support. To facilitate ticket creation, adjust user settings in the Admin Panel under Settings to allow anyone to create tickets, ensuring that registration and login are required for this process.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To properly set up your platform, start by adding agents like Jane and John in the Admin Panel under Agents -> Add New. Then, create customer accounts by adding users such as Karen and Ken in the Agent Panel under Users -> Add New. Establish service level agreements (SLAs) in the Admin Panel under Manage -> SLA, setting response times for Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, business hours). Finally, manage help topics in the Admin Panel under Manage -> Help Topics, covering critical issues like Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset. These steps will ensure efficient platform functionality and effective user support.
</p>
<br />

