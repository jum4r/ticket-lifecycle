<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/WuC4DhH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/B7dJepm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/QP0XTE5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It's time to have some fun playing around with osTicket. However, before we dive in, we need to generate a few tickets. Visit http://localhost/osTicket/ and click on "Open New Ticket." Here, we'll have the opportunity to pretend being the users we previously set up, allowing us to fabricate plausible issues or scenarios. Let's create multiple tickets, each representing different levels of severity. These can range from something simple like a password reset request to a more critical scenario like a banking website/app outage. The examples above provide some ideas for the tickets you can generate.
</p>
<br />

<p>
<img src="https://i.imgur.com/C7537Af.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We can now transition to the Admins/Agents responsible for assigning and resolving these tickets. Navigate to http://localhost/osTicket/scp/login.php and log in using the Agent credentials for the System Administrator that we set up earlier. Upon logging in, you will be presented with the recently created tickets. To begin, select one of the tickets. Here, you can make modifications to the ticket and adjust its Priority, Agent assignment, Department, Severity, and more.
</p>
<br />

<p>
<img src="https://i.imgur.com/FOD5Plq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you've assigned them, you can type a response at the bottom to simulate that you're actively addressing the issue. Alternatively, if cooperation with a different department is necessary, this is the stage where updates on the ticket's progress can be provided. Keep an eye on the logs – every time the ticket is updated, it will be automatically logged.
</p>
<br />

<p>
<img src="https://i.imgur.com/UhtuijB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Let's suppose that this issue has finally been resolved. In that case, you can provide a concise message confirming the problem's resolution. Below, under "Ticket Status" at the bottom, you can select "Resolved." Once that's completed, you can easily review closed tickets at any time. To do so, navigate to the "Tickets" section, then click on "Closed" to access a list of all previously resolved tickets. If you're new to a job, this serves as an excellent method to delve into historical tickets. It offers insight into common issues and the strategies your colleagues employed for their resolution. Feel free to continue generating new tickets for personal assignment and resolution – this serves as valuable practice.
</p>
<br />
