<p align="center">
<img src="https://imgur.com/ocgeUoz.png" alt="osTicket logo"/>
</p>

<h1>VMs - Configuring Active Directory Within Microsoft VMs </h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (version 22H2)

<h2>List of Prerequisites</h2>

- Microsoft Web Platform Installer
- OsTicket V1.15.8
- HeidiSQL

<h2>Installation Steps</h2>


<p>  
<img src = "https://i.imgur.com/FoDQra2.png" " height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>Overview</p>

<p>
<img src = "https://i.imgur.com/GFYFR0R.png" " height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
 <p>
1. Create a resource group in Azure.
</p>                                                                                                    
                                                                                                     
<p>
<img src= "https://i.imgur.com/Pk3J6Rk.png" " height="80%" width="80%" alt="Disk Sanitization Steps" />
</p>

<p>
                                                                                                 
                                                                                                 
                                                                                                 
2. Create a virtual machine within Azure.
</p>
<br />

<p>
<img src="https://i.imgur.com/dDY9AQi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. Open Remote Desktop.
</p>
<br />

<p>
<img src="https://i.imgur.com/PB1vmBe.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. Install/ Enable IIS (Internet Information Services). Windows Control Pannel < Programs and Feautures
</p>
<br />

<p>
<img src="https://i.imgur.com/yt4ZPAk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Install "Microsoft Web Platform Installer".
      - Add "MySQL 5.5"
      - Add All Simple Versions Of X86PHP Up Until 7.3
</p>
<br />

<p>
<img src="https://i.imgur.com/8ob8uQq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. Install osTicket v1.15.8.
</p>
<br />

<p>
<img src="https://i.imgur.com/SbhSS6V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Go Back To IIS, Sites->Default->osTicket, Double click PHP Manager, Enable PHP_imap.dll, Enable PHP_intl.dll, Enable PHP_opcache.dll
</p>
<br />

<p>
<img src="https://i.imgur.com/wVSvcC6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. Rename File To OST-Config.PHP And Assign Permissions To File.
</p>
<br />

<p>
<img src="https://i.imgur.com/U0zZqC1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
9. Continue Setting Up OsTicket In Browser.
  -Name Help Desk
  -Add Default Email
</p>
<br />

<p>
<img src="https://i.imgur.com/IdTzZWd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
10. Download And Install HeidiSQL.
</p>
<br />

<p>
<img src="https://i.imgur.com/0LOpcLJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
11. OsTicket Is Ready. 
</p>
<br />
