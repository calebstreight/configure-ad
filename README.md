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


- After you created your VM's make sure you change the 'Domain controller' VM's NIC to a static private IP. Now you should have a 'Client' VM and a 'Domain Controller' VM (Shown below)

![image](https://github.com/calebstreight/configure-ad/assets/162412951/8e7e9727-216f-4845-8290-72c00a9d8a03)
![image](https://github.com/calebstreight/configure-ad/assets/162412951/32b0d60f-e113-491f-95f5-b6541525cf28)


- Next, we're going to insure connectivity between both VM's so we will RDP into the 'Domain controller' VM and enable IMCPv4 on the local windows firewall so that we may send a 'ping' to the 'Domain controller' to ensure a connection. Enable the two highlighted tabs. (Shown below)

![image](https://github.com/calebstreight/configure-ad/assets/162412951/3c91e5ed-6db8-4d03-9ce8-faf0a3855370)


- After you enable IMCPv4 on the 'Domain controllers' local windows firewall, login to the 'Client' VM and ping the domain controller to ensure connection. (Shown below)

![image](https://github.com/calebstreight/configure-ad/assets/162412951/bdab2a20-08a6-49a9-a846-462dd264bc65)


- Next Install 'Active Directory' on 'Domain controller' VM. Once logged into 'Domain controller' go to Server manager > Add new roles or features > 

- Step 2
- Step 3
- Step 4


