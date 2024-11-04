# Lab-3.2-osTicket-Post-Installation
In this home lab I will be performing Sysadmin tasks on osTicket. I will be using both admin and user panels to create, configure, and assign roles and ticket settings.


Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 

End Users osTicket URL:
http://localhost/osTicket 

Acknowledge Agent Panel vs Admin Panel

Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin ![image](https://github.com/user-attachments/assets/10c4ee7c-3fdc-4b26-88fb-663dab00c0fa)


Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins ![image](https://github.com/user-attachments/assets/19763b01-5478-4dc2-88c0-f218458be69d)


Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking ![image](https://github.com/user-attachments/assets/1bebe59c-3fe6-47c0-9bf7-b3d6b316eb0c)


Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 

Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support) ![image](https://github.com/user-attachments/assets/77bac8b4-dfa6-4efa-9d25-c304d0421fd1)


Configure Users (customers)
Agent Panel -> Users -> Add New
Marty
Roman ![image](https://github.com/user-attachments/assets/acaf21b0-6ec3-4380-8519-204a250230f8)


Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours) ![image](https://github.com/user-attachments/assets/357048cf-1ed4-440c-9ac8-5c32b8be90d8)


Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other ![image](https://github.com/user-attachments/assets/5764346d-0eec-445a-a1a7-a6531220c564)


