<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents(workers)
- Configure customers
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

Log in to osTicket in admin role:

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
(Post Installation Setup)
-Configure Roles
 a. Admin Panel -> Agents -> Roles
 b. Supreme Admin
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
-Configure Departments
 a. Admin Panel -> Agents -> Departments
 b. System Administrators
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
-Configure Teams
 a. Admin Panel -> Agents -> Teams
   i. Level I Support
   ii. Level II Support
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
-Allow anyone to create tickets
 a. Admin Panel -> Settings -> User Settings
 b. Registration Required: Require registration and login to create tickets 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers)
 a. Admin Panel -> Agents -> Add New
  i. Jane
  ii. John
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
-Configure Users (customers)
 a. Agent Panel -> Users -> Add New
  i. Karen
  ii. Ken
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
-Configure SLA
  a. Admin Panel -> Manage -> SLA
   i. Sev-A (1 hour, 24/7)
   ii. Sev-B (4 hours, 24/7)
   iii. Sev-C (8 hours, business hours)

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
-Configure Help Topics
  a. Admin Panel -> Manage -> Help Topics
   i. Business Critical Outage
   ii. Personal Computer Issues
   iii. Equipment Request
   iv. Password Reset

</p>
<br />
