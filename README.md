<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-installation configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles in the Ticketing System.
- Configure Departments in the Ticketing System.
- Configure Teams in the Ticketing System.
- Configure Agents in the Ticketing System.
- Allow anyone to create tickets in the Ticketing System.
- Configure Agents ( Workers ) in the Ticketing System.
- Configure Users ( Customers ) in the Ticketing System.
- Configure SLAs ( Service Level Agreements ) in the Ticketing System.
- Configure Help Topics in the Ticketing System.

<h2>Configuration Steps</h2>

<p>
  
![image](https://github.com/teeckay/post-install-config/assets/64244011/29cd8526-595b-4254-9388-c6f3632f7981)

</p>
<p>
After installation as seen above, I began by creating a new role called a Supreme Admin, in the Admin panel for the agents. I then added permissions for tickets, tasks and knowledge base for the new role as seen below. 
</p>
<br />

<p>
  
![image](https://github.com/teeckay/post-install-config/assets/64244011/11626e5f-9891-47ee-809d-65732082860d)

![image](https://github.com/teeckay/post-install-config/assets/64244011/e59963bf-dbd5-4c23-9fff-50819e89b069)



</p>
<p>
Next I created a Level II Support team.

</p>
<br />

<p>

![image](https://github.com/teeckay/post-install-config/assets/64244011/3ec3a116-0f7f-4aa8-8fad-32d556cf44e2)
  
</p>
<p>
Next, I created a new System Administrators Department.
</p>
<br />
<p>
  
![image](https://github.com/teeckay/post-install-config/assets/64244011/acd20a00-d716-4531-bd3d-32a7ee8dc1d5)

</p>

<p>
Next, I added a new agent, Jane Doe, and put them in the system administrators department and the level ll Support Team. 
</p>
<br />

<p>
  
![image](https://github.com/teeckay/post-install-config/assets/64244011/ffae04cf-ea08-49fe-b183-e1f4732b1dd1)

</p>

<p>
 Next, I added a new user, Karen Karen, using the agent panel as an agent.

</p>
<br />

<p>

![image](https://github.com/teeckay/post-install-config/assets/64244011/e7a92a52-4b14-4e26-990f-bd334879fac8)


</p>

<p>
Next, I added a new SLA plan to be used to handle tickets. In this case, A Sev-A SLA plan with a one hour grace period and a 24 hour schedule.
</p>
<br />

<p>

![image](https://github.com/teeckay/post-install-config/assets/64244011/417c0126-851b-422c-a745-ea53faf4925b)


</p>
<p>
Next, I created a new Business Critical Outage help topic to help guide the gathered information from a user and how the ticket is routed and assigned afterwards.
</p>
<br />

<p>

![image](https://github.com/teeckay/post-install-config/assets/64244011/42e734a9-7481-430d-96e8-a1e5a7c4d632)


</p>

<p>
All done with osTicket configuration and next, triaging and solving tickets.
</p>
<br />
