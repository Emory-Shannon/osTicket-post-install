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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3>Role Creation</h3>

<p>
<img src="TS-Role Creation.PNG" height="80%" width="80%" alt="Agent Creation 1"/>
<h3></h3>
<img src="TS-Role Creation 2.PNG" height="80%" width="80%" alt="Agent Creation 2"/>
</p>
<p>
Navigate - Admin Panel->Agents->Roles. Create a role of your choosing. Ex: Supreme Admin.
</p>
<br />

<h3>Department Creation</h3>

<p>
<img src="TS-Department Creation.PNG" height="80%" width="80%" alt="Department Creation 1"/>
  <h3></h3>
<img src="TS-Department Creation 2.PNG" height="80%" width="80%" alt="Department Creation 2"/>
</p>
<p>
Navigate Admin Panel-> Agents -> Departments. Create your department of choosing. Ex: System Administrators.
</p>
<br />

<h3>Team Creation</h3>

<p>
<img src="TS-Team Creation 1.PNG" height="80%" width="80%" alt="Team Creation 1"/>
  <h3></h3>
<img src="TS-Team Creation 2.PNG" height="80%" width="80%" alt="Team Creation 2"/>
</p>
<p>
Navigate - Admin Panel -> Agents -> Teams. Team Examples: Level I Support , Level II Support.
</p>
<br />

<h3>Ticket Permissions</h3>

<p>
<img src="TS-Ticket Permission 1.PNG" height="80%" width="80%" alt="Ticket Permission 1"/>
  <h3></h3>
<img src="TS-Ticket Permission 2.PNG" height="80%" width="80%" alt="Ticket Permission 2"/>
</p>
<p>
Navigate - Admin Panel -> Settings -> User Settings.
</p>
<br />

<h3>Agent Creation</h3>

<p>
<img src="TS-Agent Creation 1.PNG" height="80%" width="80%" alt="Agent Creation 1"/>
  <h3></h3>
<img src="TS-Agent Creation 2.PNG" height="80%" width="80%" alt="Agent Creation 2"/>
</p>
<p>
Navigate - Admin Panel -> Agents -> Add New. Agent Examples: Barry, Jodie. 
</p>
<br />

<h3>User Creation</h3>

<p>
<img src="TS-User Creation1.PNG" height="80%" width="80%" alt="User Creation 1"/>
  <h3></h3>
<img src="TS-User Creation 2.PNG" height="80%" width="80%" alt="User Creation 2"/>
</p>
<p>
Navigate - Agent Panel -> Users -> Add New. User Examples: John, Karen.
</p>
<br />

<h3>SLA Creation</h3>

<p>
<img src="TS-SLA Creation 1.PNG" height="80%" width="80%" alt="SLA Creation 1"/>
  <h3></h3>
<img src="TS-SLA Creation 2.PNG" height="80%" width="80%" alt="SLA Creation 2"/>
</p>
<p>
Navigate - Admin Panel -> Manage -> SLA. SLA Examples: 
  <ul>
    <li>i. Sev-A (1 Hour, 24/7)</li>
    <li>ii. Sev B (4 Hours, 24/7)</li>
    <li>iii. Sev-C (8 Hours, Business Hours)</li>
  </ul>
</p>
<br />

<h3>Help Topic Creation</h3>

<p>
<img src="TS-Help Topic Creation.PNG" height="80%" width="80%" alt="Help Topic Creation"/>
</p>
<p>
Navigate - Admin Panel -> Manage -> Help Topics. Help Topic Examples: 
  <ul>
    <li>i. Business Critical Outage</li>
    <li>ii.Personal Computer Issues</li>
    <li>iii. Password Reset</li>
  </ul>
</p>
<br />
