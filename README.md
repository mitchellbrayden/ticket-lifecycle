<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

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
<img src="https://i.imgur.com/KwTqEe1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, log in using the admin account (e.g., Jerry).

Navigate to the Admin Panel.
Go to Agents > Departments.
Delete the Maintenance department (it may cause issues with ticket assignment).
</p>
<br />

<p>
<img src="https://i.imgur.com/BTTpoUt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As an end-user (Karen):

Log in to the osTicket system.
Open a new ticket.
In the ticket form, report the issue: "The entire online banking system is down."
Submit the ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/SQeNuP6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in to osTicket as John.
Open the ticket created by Karen.
Perform the following actions:
Set Priority to Emergency.
Set SLA to Sev-A.
Assign the ticket to the Online Banking department.
Log out as John.
Log back in as Jane.
</p>
<br />

<p>
<img src="https://i.imgur.com/SqMVQu3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in to osTicket as Jane.
Open the ticket assigned to her department.
Scroll to the bottom and click Post Reply to respond to Karen (e.g., "The issue was related to a recent update and needs a roll back.").
After resolving the issue, change the ticket status from Open to Resolved.
</p>
<br />

<p>
<img src="https://i.imgur.com/RFfI9nU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As an end-user (Karen):

Log in to the osTicket system.
Open a new ticket.
In the ticket form, report the issue: "Accounting department needs adobe upgrade, broken"
Submit the ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/QjCTd6U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in to osTicket as John.

Open the ticket.

Update the ticket:

Set SLA to Sev-B.
Assign the ticket to the Support department.
Upon learning that only two employees cannot access Adobe Reader, update the SLA:

Change SLA from Sev-B to Sev-C.
Post a reply:

"The issue could be fixed by restarting your computer." (This response will be sent to the user.)
Complete the ticket:

Change the status from Open to Resolved, as the restart resolves the issue.
Save the changes.
</p>
<br />

<p>
<img src="https://i.imgur.com/fGHneP1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As an end-user (Karen):

Log in to the osTicket system.
Open a new ticket.
In the ticket form, report the issue: "CFO's laptop will no longer turn on"
Submit the ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/4ryu3jG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log in to osTicket as John.

Open the ticket.

Update the ticket:

Set SLA to Sev-B.
Assign the ticket to the Support department.
Investigate the issue:

Learn that the laptop was plugged in.
Conclude that the charger is broken after the CFO successfully uses another laptop charger.
Resolve the ticket:

Post a reply summarizing the resolution (e.g., "The issue was caused by a faulty charger, and it has been resolved using another laptop charger.").
Change the ticket status from Open to Resolved.
</p>
<br />


