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

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles for the Supreme Admin and any members created
- Create and configure various levels of Teams
- Create a variety of agents and end users 
- Configure an SLA and a variety of severities 
- Configure some help topics

<h2>Configuration Steps</h2>

### Configuring Roles

From the admin panel in osTicket, roles were created in the Roles page under the Agents section. Adding a new role was as simple as clicking on the "Add New Role" and going from there. First, a Supreme Admin was created by creating a new role with all available permissions.
</p>
<br />

### Configuring Departments

Creating some departments was done in a similar manner as creating a role, this time using the Departments page under Agents. A new department was created with the default settings for this lab.
</p>
<br />

### Configuring Teams

Created by going into the Teams tab under Agents, teams could bring agents from various departments together. In this lab a few teams were created for later use during the Agent creation process.
</p>
<br />

### Creating Agents and Ticket Permissions

Creating Agents  was done in the Agents tab, and by simply creating credentials for 2 new "employees" that can handle tickets. These users were also assigned to the previously created departments and teams to explore the features of osTicket. In creating the credentials for these users, it allowed them to create and manage tickets alongside the supreme user account.
</p>
<br />

### Configuring Users

Some sample end users were also created for this lab. This process took place in the agent panel, doing so in the Users tab. Two of these mock end users were created for mock ticket creations later.
</p>
<br />

### Configuring SLA

The SLA was created by first opening up the "Manage" dropdown and going into the SLA page listed there. Three SLA's were created for the lab, emphasizing the different possible severities and their desired time frames.For example, the most severe SLA level was created with a 24/7 working time with a 3 hour limit on the timeframe needed to resolve the ticket.
</p>
<br />

### Creating Help Topics

This was located under the Manage tab as well. A variety of topics were added, such as a Business Critical Outage topic, a Personal Computer Issues topic, and Equipment Issues topic, and a Password Reset topic. The tickets that were created later could be created under these categories.
</p>
<br />
