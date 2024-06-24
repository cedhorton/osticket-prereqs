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
- Assign Permissions: ost-config.php
- Install Heidi SQL Database Client
- osTicket Fully Setup and Installed
- osTicket Admin Dashboard

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

![image](https://github.com/cedhorton/osticket-prereqs/assets/173581553/f9f579e7-66ef-4325-87a5-bdb0dbec2c67)

<p>
Assigned permissions in ost-config.php.  
  - Disable inheritance -> Remove All
  - New Permissions -> Everyone -> All

</p>
<br />

![image](https://github.com/cedhorton/osticket-prereqs/assets/173581553/7c6110f3-df53-4441-8727-65a5d486522b)

<p>
Downloaded and installed Heidi SQL. Created a new session. Connected to the session. Created a database called "osTicket"
</p>
<br />

![image](https://github.com/cedhorton/osticket-prereqs/assets/173581553/3e9c85d6-39bd-4a69-8f40-cda2d5a44032)

<p>
osTicket fully setup and ready to use.
</p>
<br />

![image](https://github.com/cedhorton/osticket-prereqs/assets/173581553/1c53c157-585e-467d-a30e-afd10751bc51)


<p>
Logged in to osTicket as an admin.
</p>
<br />
