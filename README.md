<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create 2 VMs
- Allow Permissions on DC-1s Firewall
- Set-up Domain


<h2>Deployment and Configuration Steps</h2>

<p>
<img src=https://i.imgur.com/bO4D8zt.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login to Azure, click create Virtual Machines. Create the domain contollers VM and its private IP address to "static". Create the clients virtual network and ensure connectivity between the domain contollers VM and the clients VM. 
</p>
<br />

<p>
<img src=https://i.imgur.com/Xsfsx8p.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Remote Desktop connect with DC-1, go to advanced settings, select inbound/outbound rules, and allow IPV4 permissions on DC-1, which will open the firewall connectivity.
</p>
<br />

<p>
<img src= https://i.imgur.com/SRuVB45.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Login into DC-1 and install Active Directory as a new Domain.
</p>
<br />
