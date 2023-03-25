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

- PHP Manager for IIS install file
- Rewrite Module file
- PHP 7.3.8 file
- VC redist.x86.exe file
- MySQL 5.5.62

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/5QUDSDA.png" height="80%" width="80%"/>
</p>
<p>
Creating a resource group and virtual machine, using Windows 10 Virtual Maching with2-4 Virtual cpus.
</p>
<br />

<p>
<img src="https://i.imgur.com/GCDlMkT.png" height="80%" width="80%"/>
</p>
<p>
Copy IP of Virtual machine, log in, and enable IIS in Windows.
</p>
<br />

<p>
<img src="https://i.imgur.com/Y2FvXPL.png" height="80%" width="80%"/>
</p>
<p>
Turn off windows features, while in programs, find internet services, proceed to world wide services, click CGI on and click ok.
</p>
<br />

<p>
<img src="https://i.imgur.com/HmR96Fv.png" height="80%" width="80%"/>
</p>
<p>
Download PhP manager for IIS, download rewrite module and install.
</p>
<br />

<p>
<img src="https://i.imgur.com/e96blXM.png" height="80%" width="80%"/>
</p>
<p>
Create a PHP file in the c drive, open the recemtly downloaded PHP, and extract the file in PHP.
</p>
<br />

<p>
<img src="https://i.imgur.com/VcMiKq0.png" height="80%" width="80%"/>
</p>
<p>
Ensure PhP file has been extracted correctly, download/install Microsoft visual C, download and install MySQL.

<p>
<img src="https://i.imgur.com/RyB0QGV.png" height="80%" width="80%"/>
</p>
<p>
Continue installation process, open IIS as an administrator.
<p>
  
<img src="https://i.imgur.com/lqwNTTG.png" height="80%" width="80%"/>
</p>
<p>
In IIS, click on PhP, click on register, and register the PhP, then reload IIS, click on osTicket, and enable: php_imap.dll, php_intl.dll, php_opache.dll.

<p>
<img src="https://i.imgur.com/KNwNIxu.png" height="80%" width="80%"/>
</p>
<p>
Refresh osTicket, reame, ost-config.php, within wwwroot folder, then include folder, then click on sampleconfig.php. Rename the sampleconfig, to just ost-config.php
</p>
<br />

<p>
<img src="https://i.imgur.com/bBy3X7X.png" height="80%" width="80%"/>
</p>
<p>
Assign permissions via properties, click on security and click advanced, disable inheritance.
</p>
<br />

<p>
<img src="https://i.imgur.com/WZ2Crtf.png" height="80%" width="80%"/>
</p>
<p>
Creating a resource group and virtual machine, using Windows 10 Virtual Maching with2-4 Virtual cpus.
</p>
<br />

<p>
<img src="https://i.imgur.com/T5pmnEE.png" height="80%" width="80%"/>
</p>
<p>
Click and remove all ineherited permissions from the object, click set principal, enter "everyone" in display box, and click check.
</p>
<br />

<p>
<img src="https://i.imgur.com/W6NC83u.png" height="80%" width="80%"/>
</p>
<p>
Enable full control for "everyone" click apply, and click okay.
</p>
<br />

<p>
<img src="https://i.imgur.com/zcWMK05.png" height="80%" width="80%"/>
</p>
<p>
Open Heidi SQL, click on unnamed and click create a new database, create database and rename to osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/6W2EnRG.png" height="80%" width="80%"/>
</p>
<p>
Continue to enter in information in osTicket; successfully installed osTicket.
</p>
<br />

<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
