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

- Create and login to the Virtual Machine using Remote Desktop Connection for Windows or download Microsoft Remote Desktop for Mac user
- Install and enable Internet Information Services (IIS) in Windows With CGI
- From the Installation Files, download and install PHP Manager for IIS, Rewrite Module, PHP 7.3.8, VC_redist.x86.exe, MySQL 5.5.62, osTicket v1.15.8
and HeidiSQL
- Enable extensions (php_imap.dll, php_intl.dll and php_opcache.dll) in IIS
- Assign Permissions to ost-config.php
- Setup osTicket and HeidiSQL then, click install

<h2>Installation Steps</h2>

1. Create and login to the Virtual Machine using Remote Desktop Connection for Windows or download Microsoft Remote Desktop for Mac user.
<p>
<img src="https://i.imgur.com/aN2EA8w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. Install and enable Internet Information Services (IIS) in Windows With CGI.
<p>
<img src="https://i.imgur.com/QA0Xb14.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. From the Installation Files, download and install PHP Manager for IIS, Rewrite Module, PHP 7.3.8, VC_redist.x86.exe, MySQL 5.5.62, osTicket v1.15.8
and HeidiSQL.
<p>
<img src="https://i.imgur.com/8jbrVR1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Enable extensions (php_imap.dll, php_intl.dll and php_opcache.dll) in IIS.
<p>
<img src="https://i.imgur.com/y9pIP7i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Assign Permissions to ost-config.php.
<p>
<img src="https://i.imgur.com/DVLfD4T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Continue setting up osTicket and HiediSQL Database in the browser then, click install.
<p>
<img src="https://i.imgur.com/Q9NuuGj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/MOSnl0c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/P9v8IUb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 7. Log in to http://localhost/osTicket/scp/login.php to test osTicket.
 <p>
<img src="https://i.imgur.com/3EVBQeo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
