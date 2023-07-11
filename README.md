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
The next step includes running IIS as an admin. From there, we would register PHP in IIS.  Now we are ready to install osTicket. 

![image](https://github.com/cblack5880/osticket-prereqs/assets/138612466/c1aa67f7-68df-4166-90a9-302c50426f3b)

There are more steps that include:

Downloading osTicket from the Installation Files Folder

Extract and copy “upload” folder to c:\inetpub\wwwroot

Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”

![image](https://github.com/cblack5880/osticket-prereqs/assets/138612466/868994dc-9afe-448a-9e8e-ac8d4f4916c3)


</p>
<p>
Once that is completed, We would have to go back to IIS and start the server over.   From here, on IIS, Go to sites -> Default -> osTicket and select “Browse *:80”

  ![image](https://github.com/cblack5880/osticket-prereqs/assets/138612466/2c5a974d-d59d-4091-aaab-04e05ca2c26f).

There would be some extenstions to enable for it to run correctly. By going back to PHP manager, we would be able to enable:

Enable: php_imap.dll

Enable: php_intl.dll

Enable: php_opcache.dll

![image](https://github.com/cblack5880/osticket-prereqs/assets/138612466/545b5985-634e-4e6d-9b55-ed4fd2c5d940)


</p>
<p>
The next step is installing HeidiSQL. This is the database client for OsTicket.   I would create a new connection to this database.  It would look like this after using MySQl credentials.

  ![image](https://github.com/cblack5880/osticket-prereqs/assets/138612466/1e66b1c4-6638-4611-b23d-be685c6ddcd0)

  Once this program is set up,  we would create a database in HediSQL callede "osTicket".

  ![image](https://github.com/cblack5880/osticket-prereqs/assets/138612466/1d87b28e-a0e8-4e80-8686-9cba7c301718)

There will be credentials that you would have to fill out in the osTicket yourself. After that, The install is complete. 

![image](https://github.com/cblack5880/osticket-prereqs/assets/138612466/5f9585a6-d53a-4ff0-983f-4e71de7269b7)

