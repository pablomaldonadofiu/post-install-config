<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Things to have in mind</h2>

- Browse to your help desk login page: "http://localhost/osTicket/scp/login.php"
- End Users osTicket URL: http://localhost/osTicket/ 
- Once inside osTicket, there are 2 options at the top right, Admin Panel and Agent Panel, these can be change by clicking them. In this tutorial we would be changing between them


<h2>Configuration Steps</h2>


<p>
Enter osTicket by going into the browser and type: localhost/osTicket/scp/login.php Enter your credentials created in the set up, then click log in. 
</p>
<p>
<img src="https://i.imgur.com/OPzIcos.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Adding Roles:</p> 
<p>As an Admin (click Admin Panel if it shows at top right), click Agents -> Roles. Inside, click “Add New Role” 
First, add the name of the new Role, Then click in Permissions and give all the permission you need. 
</p>
<p>
<img src="https://i.imgur.com/XkcoPxP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Adding Deparments:</p>
<p>As an Admin (click Admin Panel if it shows at top right), click Agents -> Deparments. Inside, click “Add New Department” . Fill the required information, And at the bottom click “create Dept”
</p>
<p>
<img src="https://i.imgur.com/bYNKAYc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Adding Teams:</p>
<p>As an Admin (click Admin Panel if it shows at top right), click Agents -> Teams. Inside, click “Add new Team”. Write a name for the team, then select Members by adding Agents. Finally click Create Team 
</p>
<p>
<img src="https://i.imgur.com/Qcst3LG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Adding Agent:</p>
<p>*Note: Agent are the people working in the ticket system.</p>
<p>As an Admin (click Admin Panel if it shows at top right), click Agents -> Agents. Inside, click “Add new Agent”. Enter Name, Email, Phone, Username and a Password ( you can select the configurations for the password). Then add Access, Permissions and/or a Team as needed. Finally click Create. 
</p>
<p>
<img src="https://i.imgur.com/2RVG49c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Adding Users:</p>
<p>*NOTE: users are the end users which create the tickets to work on. </p>
<p>As an Agent (click Agent Panel if it shows at top right), click Users, then click “Add User”. Enter Email, Full name, and Phone of the new User (this user will be able to create tickets). Then click “Add User”
</p>
<p>
<img src="https://i.imgur.com/GGxNaao.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Adding SLA:</p>
<p>As an Admin (click Admin Panel if it shows at top right), click Manage -> SLA, then Click “Add new SLA Plan”. Select name, status, grace period and schedule as require. Then click Add Plan. 
</p>
<p>
<img src="https://i.imgur.com/2xqUXY7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Adding Help Topic:</p>
<p>As an Admin (click Admin Panel if it shows at top right), click Manage -> Help Topics, then click “Add new Help Topic”. Select topic with explicit name, for example “Password Reset”. Then click on Add Topic 
</p>
<p>
<img src="https://i.imgur.com/EZbyEYp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />




