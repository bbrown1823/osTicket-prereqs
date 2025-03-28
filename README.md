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

- Within the VM (osticket-vm), download the osTicket-Installation-Files.zip and unzip it onto your desktop. The folder should be called “osTicket-Installation-Files”
- Install / Enable IIS in Windows WITH CGI
- Install PHP Manager for IIS  
- Install the Rewrite Module
- Install VC_redist.x86.exe
- Install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
    Typical Setup ->
    Launch Configuration Wizard (after install) ->
    Standard Configuration ->
    Username: root
    Password: root
- Install osTicket v1.15.8
    Unzip “osTicket-v1.15.8.zip” and copy the “upload” folder into “c:\inetpub\wwwroot”
    Within “c:\inetpub\wwwroot”, Rename “upload” to “osTicket”
- Install HeidiSQL
- 




<h2>Installation Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/993bfea5-f7d0-46f4-b26c-af57234f1046"
</p>
<p>

Here is where I downloaded the PHP Manager for IIS in the osTicket files folder. This simplifies the management of PHP settings by:
- Allowing for easier PHP configuration
- Enabling FastCGI for PHP
- Managing PHP Extensions
- Improving Performance & Stability
- Simplifing Troubleshooting

</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/2b144e00-0007-4853-9783-ccaeb3b3a98c"
</p>
<p>

Here is where I had to installed the IIS Rewrite Module for osTicket because it helps with URL rewriting and redirection, ensuring that clean and user-friendly URLs work correctly. This is important because:
- Friendly URLs Support
- Eliminates index.php in URLs
- Ensure Proper Redirection
- Ehances Security
- Required for .htaccess Equivalent
- 

</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/1a881620-58a5-48a3-9b97-a13e6b5284eb"

</p>
<p>

    
Here is where I installed  (VC_redist.x86.exe.) for osTicket, PHP requires it to function properly
- This required for PHP Execution
- Is needed for PHP Extensions
- Ensure Stability & Compatibility
- PHP on Windows Requires the x86 version

</p>
<br />
