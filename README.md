<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- PHP Manager for IIS 
- Rewrite Module 
- Internet Information Services (IIS)
- My SQL Server (5.5.62 Version used)
- HeidiSQL

<h2>Installation Steps</h2>
*This is noted that I have already created my resource group and virtual machine from Azure. I used the Virtual machine to create my Remote Desktop, and I am now ready to install OsTicket.
<p>

>
</p>
<p>
First, I would install PHP manager, follow by the "Rewrite Module." These are simple installers needed to actually run the installer for OSTicket. I would then set up the actual PHP Installer.

(https://github.com/cblack5880/osticket-prereqs/assets/138612466/2661e23e-7e7d-4b0a-96e4-29a4215f6e83)
(https://github.com/cblack5880/osticket-prereqs/assets/138612466/20b39303-337f-4db3-9c77-24b64ec771b9)

Next I would download and install VC_redist.x86.exe and MySQL 5.5.62. Mysql should now be adding a server om the coomputer for OsTicket to store data for the program.

![image](https://github.com/cblack5880/osticket-prereqs/assets/138612466/3d57b89d-183d-4287-9bec-742c777dafd1)

<br />
The next step includes running IIS as an admin. From there, we would register PHP in IIS

![image](https://github.com/cblack5880/osticket-prereqs/assets/138612466/c1aa67f7-68df-4166-90a9-302c50426f3b)


<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
# osticket-prereqs
