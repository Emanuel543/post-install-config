<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation]

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Have a VM with osTicket installed


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/3Y4CAcm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
How to Configure Roles
   <p>
Admin Panel -> Agents -> Roles -> Name user "Supreme Admin"


Give this role access to all permissions on the "permissions" tab
</p>
<br />

<p>
<img src="https://i.imgur.com/UZqEJSl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments
  </p>
Admin Panel -> Agents -> Departments Name it -> Name it "System Administrators"

</p>
<br />

<p>
<img src="https://i.imgur.com/jO4M5Hd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams
   </p>
Admin Panel -> Agents -> Teams -> Name it

</p>
<br />

<p>
<img src="https://i.imgur.com/uyK307a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
   Allow anyone to create tickets
   </p>
Admin Panel -> Settings -> User Settings

Registration Required: Require registration and login to create tickets(make sure is not checked)

</p>
<br />

<p>
<img src="https://i.imgur.com/SJMC67y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers)
  </p>
Admin Panel -> Agents -> Add New

</p>
<br />

<p>
<img src="https://i.imgur.com/Oq6l3Nf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers)
   
Agent Panel -> Users -> Add New

</p>
<br />

<p>
<img src="https://i.imgur.com/C9Ke1eK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
   
Admin Panel -> Manage -> SLA
   
   Sev-A (1 hour, 24/7)     
   Sev-B (4 hours, 24/7     
   Sev-C (8 hours, business hours)

</p>
<br />
