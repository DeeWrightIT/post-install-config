<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- To create new roles, departments, teams, agents, and users. Also, to create new SLAs (Service Level Agreements) and to assign common and uncommon help to topics to each service level. 

<h2>Configuration Steps</h2>

<img width="899" height="502" alt="Screenshot 2025-11-25 125852" src="https://github.com/user-attachments/assets/b32e6f44-9d3a-4886-ae4a-ef695027a9e2" />

<p>
First, I configured the role of an administrator "supreme admin".
I went to the Admin Panel, then Agents, Roles, and assigned roles to the admin.

</p>
<br />

<img width="921" height="488" alt="Screenshot 2025-11-25 130055" src="https://github.com/user-attachments/assets/4e869e88-69c8-40d8-bf8c-a1c5bf04410d" />

<p>
Next, I configured the "system administrators" department by going to the Admin Panel, Agents, Departments, 
</p>
<br />

<img width="857" height="508" alt="Screenshot 2025-11-25 130226" src="https://github.com/user-attachments/assets/b6c1dcb5-3973-40e2-8a4d-eb2622436678" />

<p>
Then, I made two teams. One for level I support and the other level II support. To do this, I went to the Admin Panel, Agents, and Teams
</p>
<br />

<img width="857" height="508" alt="Screenshot 2025-11-25 130226" src="https://github.com/user-attachments/assets/4a2d1552-b9b4-4cd8-86f2-ec845f2f362b" />

<p>
Next, I allowed anyone to create tickets as long as they were registered users. I did this by going to Admin Panel, Settings, User Settings. There's a box to check that would require user registration to create a ticket. 
</p>
<br />

<img width="894" height="471" alt="Screenshot 2025-11-25 130458" src="https://github.com/user-attachments/assets/3cdf529b-e884-4731-a8aa-9c54592c5c16" />

<p>
Afterwards, I created two new agents by going to Admin Panel, Agents, and Add New. I made two new users, John Doe and Jane Doe.
</p>
<br />

<img width="905" height="472" alt="Screenshot 2025-11-25 130909" src="https://github.com/user-attachments/assets/937916e7-be5c-4108-8394-ec3a7288f933" />

<p>
I also created two new users, Karen and Ken, to create new tickets. To create new users I went to the Agent Panel, Users, and Add New
</p>
<br />

<img width="884" height="455" alt="Screenshot 2025-11-25 131008" src="https://github.com/user-attachments/assets/bce8132c-c68c-408f-89ed-dbe5bd577781" />

<p>
Next, I configured SLA Plans by going to Admin Panel, Manage, SLA. I created three plans and assigned when these should be serviced, Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours)
</p>
<br />

<img width="892" height="477" alt="Screenshot 2025-11-25 131257" src="https://github.com/user-attachments/assets/806f6502-3da2-4554-a197-4ec9fb6c0ec7" />


<p>
Last, I configured help topics and assigned then to certain severites based on the topic.
</p>
<img width="873" height="485" alt="Screenshot 2025-11-25 131424" src="https://github.com/user-attachments/assets/bb948607-90b2-47e0-96b0-f802e7a61dd8" />


<br />
