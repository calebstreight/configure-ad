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
- Windows 10 (21H2)

<h2>Deployment and Configuration Steps</h2>

- First you want to create two Virtual Machines in Microsoft Azure, make sure one is using 'Windows 10' and the other one is using 'Windows Server'. The one using 'Windows Server' will be our 'Domain Controller'. Make sure both VM's use the SAME VNET. (Shown below)

![image](https://github.com/calebstreight/configure-ad/assets/162412951/125b3b55-5d70-4637-97cd-64ddf79b0f96)


- After you created your VM's make sure you change the 'Domain controller' VM's NIC to a static private IP. (Shown below)

![image](https://github.com/calebstreight/configure-ad/assets/162412951/8e7e9727-216f-4845-8290-72c00a9d8a03)

- Step 2
- Step 3
- Step 4


