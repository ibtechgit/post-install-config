<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
</p>
This walkthrough demonstrates the post-install configuration of the osTicket system.<br />

<p>

</p>
</p>
<p>
After successfully configuring osTicket from scratch you will do some system administration and work on some post installation setup.
First, you will configure new roles within the help desk. In order to do that, go to Admin panel > Agents > Roles and create a Supreme Admin. 
Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since you are creating a Supreme Admin they will be given "all permissions". Keep in mind, roles are used to determine an agent's permissions so, not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this
</p>
<img src="https://i.imgur.com/XHteqdt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
Select the "Departments" button in the agents tab. Here you will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case, you will be creating the "System Administrators" department. This is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab. 
</p>
<br />
<p>
<img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring a new department, set up a new team. Teams allow you to pull agents from different departments. You can have an A-team that has top technicians from specific departments. For example: you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team, go to Agents > Teams. A Level I support team has been created by default; in this example you will create a Level II Support Team. 
</p>
<br />
<p>
<img src="https://i.imgur.com/cYzWBD2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that you've set up a new team, you will create a new setting that will allow anyone to create tickets. Admin Panel > Settings > User Settings.

</p>
<br />
<img src="https://i.imgur.com/H1q2Fdh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are assigned using the Agents tab. 
</p>
<br />
<img src="https://i.imgur.com/8WTOSre.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path: Agent Panel > Users > User Directory > Add new. 
</p>
<br />
<img src="https://i.imgur.com/xOprA9f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLA Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel > Manage > SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period. 
</p>
<br />
<img src="https://i.imgur.com/LpjCaLd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help topics help users categorize their tickets. In the example below, a help topic for "Business Critical Outage" has been made. This topic can be chosen if customers cannot access mobile banking. 
</p>
<br />
<img src="https://i.imgur.com/kB7rts2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
