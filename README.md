<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration and creating accounts of the open-source help desk ticketing system osTicket.
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Admin Roles and Teams
- Create Employee Accounts
- Create User Accounts
- Configure Service Level Agreements
- Create Help Topics

<h2>Configuration Steps</h2>

<p>
  
![image](https://github.com/ijoshua932/post-install-config/assets/139269375/b4870b1f-7253-49eb-8918-c51e25047882)
</p>
<p>
If you have successfully filled in all the necessary information during the setup process of osTicket, you should see the osTicket interface or dashboard. This interface typically displays options to manage tickets, configure settings, and interact with your support system. Additionally, you may notice various features like ticket queues, ticket search, and customer interactions, indicating that osTicket has been set up correctly.
</p>
<br />

<p>

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/4b0bc54e-c92e-4a38-816b-e07ece13b898)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/73e6b56b-8007-4e78-85c6-2aab850d493f)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/2ceda0a3-2014-404e-9829-aa9c26c22d79)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/dff9a47a-a8c1-45e3-a942-4027dd344495)

</p>
<p>
Once logged in as an administrator, navigate to the "Admin Panel" section in the top right corner of the osTicket interface. To create a new role, go to the "Roles" page and click on the "Add New Role" button. Fill in the required information such as role name, description, and set the desired permissions for the new role before saving it.
</p>
<br />

<p>
  
![image](https://github.com/ijoshua932/post-install-config/assets/139269375/5097f47d-fa28-4976-8b92-abb0dce7eea1)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/5a5ee441-e1e7-4be2-874a-3922922e68e2)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/cbea4960-a73b-42c8-923b-da09a23e9aa3)
</p>
<p>
To create a new department in osTicket, navigate to the "Admin Panel" section. From there, select "Departments." Click on the "Add New Department" button and provide the necessary details such as department name, email address, and any other relevant information. Save the changes, and the new department will be created.
</p>
<br />

<p>
  
![image](https://github.com/ijoshua932/post-install-config/assets/139269375/d3aea772-e97b-45f6-9a69-22abd7f331af)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/fafbdb02-3ed2-4eb9-ada7-2cb042155032)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/9df9d2f7-d2b2-48d3-9f1d-c89ce457d506)
</p>
<p>
Creating a new team in osTicket involves the following steps, navigate to the "Admin Panel" section. From there, select "Teams." Click on the "Add New Team" button and provide the required information such as team name, team leader, and any other relevant details. Save the changes, and the new team will be created.
</p>
<br />

<p>

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/4b0bc54e-c92e-4a38-816b-e07ece13b898)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/db313a57-073a-46cb-8800-e15dea798868)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/ae042d04-9a65-4e0f-a102-f51e1fb560fd)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/b447a382-3345-4437-950c-d33175d20690)
</p>
<p>
To create new agents in osTicket, follow these steps:

- Navigate to the "Admin Panel" section and followed by "Agents."
- Click on the "Add New Agent" button and fill in the agent's details, such as their name, email address, and desired username and password.
- Assign the agent to the relevant departments and teams by selecting the checkboxes next to their names.
- Save the changes, and the new agent will be created, allowing them to log in and start handling support tickets.
</p>
<br />

<p>

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/9b4cbe6b-76ef-463b-964a-dfb37b2ce5ec)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/3611b159-a2c4-4eda-86b1-408a7da233f5)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/6f5260cf-cbb4-4a9c-84ea-fe67f49bfc77)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/2d3f62e3-a0f3-45cc-a56f-aa4eda078317)
</p>
<p>
To create new users in osTicket, follow these steps:

- Navigate to the "Agent Panel" section followed by "Users."
- Click on the "Add New User" button and provide the user's details such as their name, email address, and desired username and password.
- Assign the user to the appropriate user group and set any additional permissions or preferences.
- Save the changes, and the new user will be created, allowing them to access the user portal and submit support tickets.
</p>
<br />

<p>

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/1017f2aa-361c-4eb4-98ae-cfcdc339c27f)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/097edc9b-d3ca-4f6f-b828-e5e74459be06)
</p>
<p>
To create a new SLA (Service Level Agreement) in osTicket, follow these steps:

- Navigate to the "Admin Panel" section followed by "SLAs."
- Click on the "Add New SLA" button and provide the necessary details such as the SLA name, response and resolution times, and any other criteria you want to include.
- Configure the escalation rules and actions as per your requirements.
- Save the changes, and the new SLA will be created, allowing you to apply it to departments or tickets to enforce the defined service level targets.
</p>
<br />

<p>

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/d1052b5a-52e7-477b-9a5b-67e33813de80)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/4178ec13-9534-4e77-b2d4-8c4ea574e758)

![image](https://github.com/ijoshua932/post-install-config/assets/139269375/f294c0e8-bf32-4d58-a17f-342c3b8a3a85)
</p>
<p>
To create new help topics in osTicket, follow these steps:

- Navigate to the "Admin Panel" section followed by "Help Topics."
- Click on the "Add New Help Topic" button and provide the necessary details such as the help topic name, description, and any relevant notes.
- Set the visibility and access permissions for the help topic as needed.
- Save the changes, and the new help topic will be created, allowing you to assign it to tickets and organize your support content effectively.
</p>
<br />
