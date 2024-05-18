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
<img width="994" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/a1fd63c3-737f-4398-97e5-6113521ae0c9">
<img width="1190" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/b2dad0d0-b7af-49aa-ba36-0efe47108c47">


<p>
<img width="1180" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/0b1e0042-d585-4219-a724-7c385da519ab">

 <img width="961" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/18863cbb-62fc-42d5-8b38-d18087ea3e82">

</p>
<p>
(Post Installation Setup)
-Configure Roles
 a. Admin Panel -> Agents -> Roles
 b. Supreme Admin
</p>
<br />

<p>
<img width="971" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/61effcfe-044a-4613-8556-62bbd8b78a27">

</p>
<p>
-Configure Departments
 a. Admin Panel -> Agents -> Departments
 b. System Administrators
<img width="962" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/6513d4b8-068b-4520-9e90-2233a8026a7e">

</p>
<br />

<p>
<img width="952" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/fe3c37de-e51f-45fa-8a53-b9fc0ae7d63a">
</p>
<p>
-Configure Teams
 a. Admin Panel -> Agents -> Teams
   i. Level I Support
   ii. Level II Support
</p>
<br />

<p>
<img width="964" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/d2e463ed-3017-4ece-bf03-3360525b654b">
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
<img width="959" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/5a9387cf-0bed-4b31-89bb-19343765b13c">


  ii. John
 <img width="955" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/ff9b57d0-8899-4742-9162-376f385e9f75">

</p>
<br />

<p>
 
</p>
<p>
-Configure Users (customers)
 a. Agent Panel -> Users -> Add New
  i. Karen
 <img width="1114" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/b66e8916-8b18-45db-b0f0-c713382aba12">

  ii. Ken
  <img width="958" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/8724e23c-c765-4d64-abea-50d0c1673d5d">

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
-Configure SLA
  a. Admin Panel -> Manage -> SLA
 <img width="969" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/691e2aac-03b4-4035-8cbe-ae937493889c">

   i. Sev-A (1 hour, 24/7)
  <img width="960" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/b46a331e-729c-4ae0-9a77-7bdbb0222d37">

   ii. Sev-B (4 hours, 24/7)
 <img width="961" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/9301f3dd-34b2-4755-a5ff-ac2f7cbcf017">

   iii. Sev-C (8 hours, business hours)
<img width="952" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/fee3c0b2-b3c5-4e67-abcc-5b4c3d20e8b9">

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
-Configure Help Topics
  a. Admin Panel -> Manage -> Help Topics
   i. Business Critical Outage
 <img width="957" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/459843b0-c871-4a36-a359-37e474c9a9cb">

   ii. Personal Computer Issues
 <img width="963" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/e2e36e52-5ac8-4c5b-9191-4e0ae0c27870">

   iii. Equipment Request
   <img width="963" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/391b9b54-367e-420c-a2cb-56c8c6cf5d0e">

   iv. Password Reset
<img width="964" alt="image" src="https://github.com/dteimuno/post-install-config/assets/169619672/d8b7d1f2-929d-4455-9b0c-10e60ac5d781">


</p>
<br />
