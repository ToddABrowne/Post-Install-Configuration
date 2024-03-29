<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/462PQ05fKAA)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Open IIS as an Admin
- Register PHP from within IIS and Restart IIS
- Install osTicket v1.15.8 and Restart IIS
- Go to site > Default > osTicket "Browse *80"
- Enable Extensions
- Assign Permissions
- Download and Install HeidiSQL

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/WR6scUI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
</p>
<img src="https://i.imgur.com/enfk7oN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
<img src="https://i.imgur.com/lB8ZEQh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
Opening and running IIS as an Admin is mandatory when inputting settings. Registering PHP within IIS allows the web server to reconize and properly handle PHP files. By configuring IIS to work with PHP, you enable it to interpret PHP code within the web pages, enabling dynamic content generation. Restarting the IIS is to refresh the system with the new registeration settings.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJBk3sv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
</p>
<img src="https://i.imgur.com/tpODsFD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<img src="https://i.imgur.com/mjmL1rz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
Downloading, installing, copying file to root folder on C drive, and finally renaming file as osTicket. By clicking the "Browse *80" link to the right of the second screenshot, produced the osTicket local host setup page. Enabling the PHP extensions simplifies the process of managing PHP installations and settings for websites hosted on IIS, making it easier to ensure compatability and optimal performance.

</p>
<br />

</p>
<img src="https://i.imgur.com/mEmjArW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
<img src="https://i.imgur.com/T1uTB8t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
<img src="https://i.imgur.com/QQb8T4i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
<p>
After enabling more features from PHP Extension. I went ahead and assigned permission to everyone at this time. The final download and install before the post installation setup is HeidiSQL. HeidiSQL is a free and open-source database management tool primarily designed for MySQL, Microsoft SQL Server, and PostgreSQL. HeidiSQL main purpose is to provide developers and database administrators with user-friendly interface to manage, edit, and interact with databases efficiently.
</p>
<br />
