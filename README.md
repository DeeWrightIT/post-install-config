<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- To create new roles, departments, teams, agents, and users. Also, to create new SLAs (Service Level Agreements) and to assign common and uncommon help to topics to each service level. 

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/xHP4qyy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, I configured the role of an administrator "supreme admin".
I went to the Admin Panel, then Agents, Roles, and assigned roles to the admin.

</p>
<br />

<p>
<img src="https://i.imgur.com/71mPva0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I configured the "system administrators" department by going to the Admin Panel, Agents, Departments, 
</p>
<br />

<p>
<img src="https://i.imgur.com/M9a4F1m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then, I made two teams. One for level I support and the other level II support. To do this, I went to the Admin Panel, Agents, and Teams
</p>
<br />

<p>
<img src="https://i.imgur.com/vpDotW7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I allowed anyone to create tickets as long as they were registered users. I did this by going to Admin Panel, Settings, User Settings. There's a box to check that would require user registration to create a ticket. 
</p>
<br />

<p>
<img src="https://i.imgur.com/pxXG3jB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Afterwards, I created two new agents by going to Admin Panel, Agents, and Add New. I made two new users, John Doe and Jane Doe.
</p>
<br />

<p>
<img src="https://i.imgur.com/QZyi38G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I also created two new users, Karen and Ken, to create new tickets. To create new users I went to the Agent Panel, Users, and Add New
</p>
<br />

<p>
<img src="https://i.imgur.com/8wkzcJQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I configured SLA Plans by going to Admin Panel, Manage, SLA. I created three plans and assigned when these should be serviced, Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://i.imgur.com/ARwdbdA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Last, I configured help topics and assigned then to certain severites based on the topic.
</p>
<br />
