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

- Installed/Enabled IIS with CGI
- Installed PHP Manager for IIS
- Create the directory C:\PHP
- Download and Install MySQL
- Open IIS as an Admin and register PHP from within IIS
- Install osTicket v1.15.8
- Item 7
- Item 8

<h2>Installation Steps</h2>

![image](https://github.com/cedhorton/osticket-prereqs/assets/173581553/aaf61bb8-50b8-4002-91be-66a9302eda51)

Installed/Enabled IIS in Windows with CGI and common HTTP features and IIS managment console. 
  - World Wide Web Services -> Application Development Features -> [X] CGI [X] Common HTTP Features
  - Internet Information Services -> Web Management Tools -> IIS Management Console [X] IIS Management Console.


</p>
<br />

![image](https://github.com/cedhorton/osticket-prereqs/assets/173581553/68296aa1-1923-467f-aa77-afc450e72bc5)

<p>
Downloaded and installed PHP Manager for IIS and the Rewrite Module.
</p>
<br />

![image](https://github.com/cedhorton/osticket-prereqs/assets/173581553/28392fb2-d0ed-4812-938e-800be1b5d986)

<p>
Downloaded PHP and created a PHP folder inside Windows (C:) and extracted the contents into C:\PHP folder
</p>
<br />

![image](https://github.com/cedhorton/osticket-prereqs/assets/173581553/8c1d7d8a-a3b1-4f27-a35e-2da0eade4b8f)

<p>
Downloaded and installed MySQL server and setup credentials for root.
  Typical Setup -> 
  Launch Configuration Wizard (after install) -> 
  Standard Configuration -> (Set Password)

</p>
<br />

![image](https://github.com/cedhorton/osticket-prereqs/assets/173581553/7c88b2c9-b8e1-4e22-bca6-c501563984f1)

<p>
Clicked "Start" on windows, searched "IIS" and right clicked to run as administrator and registered PHP from within IIS.
</p>
<br />

![image](https://github.com/cedhorton/osticket-prereqs/assets/173581553/5b4ae3c1-5e7c-435a-8f37-a78375bbbf89)

<p>
Downloaded osTicket
Extracted and copied “upload” folder to c:\inetpub\wwwroot
Within c:\inetpub\wwwroot, Renamed “upload” to “osTicket”

</p>
<br />

<p>
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
