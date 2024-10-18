<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Building a Help Desk Ticketing System: From Server Setup to Ticket Resolution with osTicket</h1>
In this project, I installed and configured osTicket, an open-source help desk system, on a virtual machine hosted in Microsoft Azure. I used Remote Desktop to manage the VM, set up IIS as the web server, and walked through the entire lifecycle of ticket management within osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure: Virtual Machines
- Remote Desktop: To access the VM
- IIS: Web server setup for osTicket
- Windows 10 Pro: Operating system on the VM

<h2>Prerequisites</h2>
To ensure a smooth installation of osTicket, I first installed the necessary prerequisites:

- MySQL: As the database for osTicket.
- HeidiSQL: For managing the osTicket database.
- PHP & PHP Manager: To handle the server-side scripting.
- VC Redist & URL Rewrite: Dependencies for running PHP on IIS.

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Prepare Windows 10 as a Web Server: I installed and enabled IIS, along with the required application features and the IIS Management Console.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Required Components:

- Installed PHP Manager, VC Redist, Rewrite Module, and PHP.
- Installed mySQL and set it up for database management with HeidiSQL.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install osTicket:

- Downloaded and extracted the osTicket files, placed them in the IIS root directory, and configured it as a website.
- Tested to ensure osTicket was running properly through IIS.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enable Features and Set Permissions:

- Enabled necessary PHP extensions and assigned proper file permissions for security and functionality.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Complete Setup:

- Registered osTicket, connected it to mySQL, and completed the setup process.
</p>
<br />

<h2>Post-Installation Configuration:</h2>
<p>
After the installation, I configured osTicket to function as an efficient help desk system:
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Set up Roles, Departments, and Teams:

- Created roles for administrators and agents and set up teams for different support levels (e.g., Level 1 and Level 2).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Add Agents and Users:

- Added support agents and end-users who would be interacting with the ticket system.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Establish SLAs (Service Level Agreements):
  
- Defined response times for various ticket priorities, such as a 1-hour response for critical issues (Sev-A).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create Help Topics:

- Set up help topics to categorize user requests, like "Password Resets" or "Equipment Requests."
</p>
<br />

<h2>Managing the Ticket Lifecycle:</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ticket Creation: Users or agents submit tickets via the help desk.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Ticket Assignment: Tickets are assigned based on priority and category.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Resolution and Closure: Agents resolve the issues, communicate with users, and close tickets once verified.
</p>
<br />

<h2>Conclusion:</h2>

<p>
This project gave me hands-on experience with setting up and managing a help desk system, demonstrating my ability to configure both the backend and operational side of IT ticket management.
</p>
<br />
