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
- Configure SLAs
- Configure Help Topics

- <h2>Configuration of Roles</h2>
1. Admin Panel -> Agents -> Roles
2. Supreme Admin

![1](https://i.imgur.com/MTE2IPV.jpeg)

Create the role Supreme Admin, and give it the accessbility that a supreme admin should have. Complete Control.

![2](https://i.imgur.com/uwz8rea.png)

- <h2>Configure Departments<h2>
1. Admin Panel -> Agents -> Departments
2. System Administrators

![3](https://i.imgur.com/1AcbOUD.jpeg)

- <h2>Configure Teams<h2>
1. Admin Panel -> Agents -> Teams
2. Level I Support
3. Level II Support

![4](https://i.imgur.com/HS0toB5.jpeg)

- <h2>Allow anyone to create tickets<h2>
1. Admin Panel -> Settings -> User Settings
2. Registration Required: Require registration and login to create tickets

![5](https://i.imgur.com/EYjjPlt.jpeg)

**Feel free to use any name to your liking !**

- <h2>Configure Agents<h2>
1. Admin Panel -> Agents -> Add New
2. Layla (I set Layla to be a System Admin and role as Supreme Admin)
3. Jamari (I set Jamari as Maintenance)
![6](https://i.imgur.com/VFzN7z3.jpeg)

Unselect " Send the agent a password reset email" , then enter a regular password like "Passsword1" or anything of your liking. 
Unselect "Require password reset next login" , just to avoid the hassle. 

![7](https://i.imgur.com/KyLuEAu.jpeg)

Now, Create. 

- <h2>Configure Users<h2>
1. Agent Panel -> Users -> Add New
2. Dimitri
3. Byleth
![8](https://i.imgur.com/La5tV1E.jpeg)

- <h2>Configure SLA<h2>
1. Admin Panel -> Manage -> SLA
2. Sev-A (1 hour, 24/7)
3. Sev-B (4 hours, 24/7)
4. Sev-C (8 hours, business hours)
![10](https://i.imgur.com/FVBR0zp.jpeg)
![11](https://i.imgur.com/NlCmYou.jpeg)

It should look like this when you set up all Sev-Types.
![12](https://i.imgur.com/4eeYZEW.jpeg)

- <h2>Configure Help Topics<h2>
1. Admin Panel -> Manage -> Help Topics
![13](https://i.imgur.com/dodgai7.jpeg)
2. Business Critical Outage
3. Personal Computer Issues
4. Equipment Request
5. Password Reset

![14](https://i.imgur.com/M8P0LIT.png)

It should look like this 

![15](https://i.imgur.com/MKe9rTz.jpeg)

Update the New Ticket Options and follow the steps above. 

On the [next tutorial](https://github.com/fnabeel/osTicket---Ticket-Lifecycle-Intake-Through-Resolution), we will create Tickets and showcase the Ticket Lifecycle.
