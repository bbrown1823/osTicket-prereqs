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
<img src="https://github.com/user-attachments/assets/678eb6e0-9f65-4b2d-8b8b-49dce18ef174"
    </p>
<img src="https://github.com/user-attachments/assets/19a37a98-264a-4fdd-be46-35b62b10d1c7"
    </p>
<img src="https://github.com/user-attachments/assets/78eb5a07-e11b-471f-9693-6bb71549f3a9"
    </p>
<img src="https://github.com/user-attachments/assets/95cc715a-ebb1-4d0f-a158-cd5af6b11fe9"
    </p>
<img src="https://github.com/user-attachments/assets/82eb6261-1f04-4116-b301-ee35d367327b"
    </p>
<img src="https://github.com/user-attachments/assets/5271ccd3-5611-40b9-90fd-9491c9af8b26"
    </p>
<img src="https://github.com/user-attachments/assets/fb48c695-dfb1-471c-83b8-13c261f22c42"
    </p>
<img src="https://github.com/user-attachments/assets/2fb94f44-ba23-403c-a4a6-9b233171458d"
    </p>
<img src="https://github.com/user-attachments/assets/2d0621d5-1afa-40a3-97e5-fcd33e01fb9c"
    </p>
<img src="https://github.com/user-attachments/assets/8f6871f9-945f-4ed2-96c2-55b040c44d29"
    </p>
<img src="https://github.com/user-attachments/assets/3987d823-e439-4d0d-b817-5abf93afdc16"
    </p>
<img src="https://github.com/user-attachments/assets/fef62c2b-de09-4e3e-8427-111297ffd0e7"
    </p>
<img src="https://github.com/user-attachments/assets/7679708b-63b6-4a8c-87d0-565731cda7a6"
    </p>
<img src="https://github.com/user-attachments/assets/2bef8145-6d74-4219-8d6e-fbb6ad99b573"
    </p>
<img src="https://github.com/user-attachments/assets/747ca5d2-efc4-4474-bc1e-90367d7282ef"
    </p>
<img src="https://github.com/user-attachments/assets/e4f15331-1797-42a9-83f0-2a42d16b915b"


    











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
