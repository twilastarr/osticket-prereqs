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

- Enable Internet Information Services
- Install Web Platform
- Install MySql
- Install OS Ticket
- Configure  Permisson

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/8S66dqL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to control panel within your remote connection and click on programs. Then click on "Windows feature on or off" then enable Interent Information Services & Worldwide Web Services. Expand Internet Information Services and expand Worldwide Web and select and enable GCI.
</p>
<br />

<p>
<img src="https://i.imgur.com/NWQ1Ntp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open IIS as an Admin

Register PHP from within IIS

Reload IIS (Open IIS, Stop and Start the server)

Reload IIS (Open IIS, Stop and Start the server)

</p>
<br />

<p>
<img src="https://i.imgur.com/NWQ1Ntp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Install osTicket v1.15.8
Download osTicket from the Installation Files Folder
Extract and copy “upload” folder to c:\inetpub\wwwroot
Within c:\inetpub\wwwroot, Rename “upload” to “osTick

Reload IIS (Open IIS, Stop and Start the server)

</p>
<br />
<img src="https://i.imgur.com/NWQ1Ntp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


