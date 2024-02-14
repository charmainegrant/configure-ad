<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Domanin controller and Client-1 Virtual Machine in Azure
- Ensure connectivity between domain controller and Client-1
- Install Active Directory
- Create an Admin and Normal user account in Active Directory
- Join Client-1 to your domain (mydomain.com)
- Set-up Desktop for non-administrative users on Client-1
- Create additional users and attempt to log into Client-1 with one of the users

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://imgur.com/FInJOOb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Add roles and features -> Click Next through each screen -> Install
</p>
<br />

<p>
<img src="https://imgur.com/UabKRw9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After installing Active Directory, promote it to a Domain Controller. Set up a new forest and name it (mydomain.com) for example.
</p>
<br />

<p>
<img src="https://imgur.com/QJU9qjh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create Organizationl Units
</p>
<br />
