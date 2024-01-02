<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This is a step by step outlines of the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Install / Enable IIS in Windows
- Install the Rewrite Module
- Install MySQL/ and set the user name and Password
- Install C++ Redistributable
- Configure Permission and Install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/n3NOQqo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>
To install Internet Information Services (IIS) on Windows 10, access the Control Panel, navigate to "Programs" > "Turn Windows features on or off," and check "Internet Information Services" in the list. Optionally, select additional components like CGI and Common HTTP Features. Apply changes, restart your computer if prompted, and verify the installation by accessing "Internet Information Services (IIS) Manager." 
</p>
<br />Install the Rewrite Module

<p>
<img src="https://i.imgur.com/9kkCokh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />Install MySQL/ and set the user name and Password

<p>
<img src="https://i.imgur.com/HuEdeln.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<img src="https://i.imgur.com/4BvAF8P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>

  
<img src="https://i.imgur.com/IdcQoxc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



</p>
<br /> Install C++ Redistributable

<img src="https://i.imgur.com/S0jZjFG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


</p>
<p>

</p>

<br /> Configure Permission and Install osTicket

<p>
<img src="https://i.imgur.com/jK8FOHA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/y3Td3iF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>

To set up osTicket v1.15.8, begin by opening Internet Information Services (IIS) as an administrator. Register PHP within IIS by adding a new module mapping in the Handler Mappings section. After registering PHP, reload IIS by stopping and starting the server. Next, download osTicket v1.15.8 from the provided Installation Files Folder and extract the contents. Locate the "upload" folder and copy it to "c:\inetpub\wwwroot." Once copied, rename the "upload" folder to "osTicket." These steps facilitate PHP registration in IIS and enable the installation of osTicket v1.15.8 by transferring the necessary files to the web root directory, readying the environment for osTicket setup and configuration. Adjust settings according to osTicket's specific requirements and configurations as needed.
</p>
