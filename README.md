# osTicket Post Installation Configuration

## Environments and Technologies Used

- Microsoft Azure
- Virtual Machines
- osTicket

## Operating Systems Used 

- Windows 10 Pro, version 22H2 - x64 Gen2

## Configuration Steps

1. Configure Roles
2. Configure Departments
3. Configure Teams
4. Configure Agents
5. Configure Users
6. Configure SLA (Service Level Agreement)
7. Configure Help Topics


### Login to the agent portal

Username: LabADMIN
Password: osTicketPassword123!

http://localhost/osTicket/scp/login.php

Click on admin panel on the top right 

![image](https://github.com/user-attachments/assets/c6355bcc-14ae-4b2c-a16d-31fcb8ced5bf)

### Configure Roles

We will configue a role of "Super User" to gain an understanding about how roles work in osTicket

Navigate to Agents > roles > Add New Role

![image](https://github.com/user-attachments/assets/6c990541-f440-4b03-a683-6f26657c5b5d)

Name the new role  `Super User` then navitage to the "Permissions tab" and select all boxes in Tickets, Tasks, Knowledgebase  

Take note of some of the permissons we can assign to roles

#### Tickets Permissions    

![image](https://github.com/user-attachments/assets/baf21f62-c83d-413a-bee9-341ccd99e944)

#### Tasks Permissions  

![image](https://github.com/user-attachments/assets/0380a834-13e5-4969-8b6e-fe0773f844a6)

#### Knowledgebase Permissions  

![image](https://github.com/user-attachments/assets/6dd4f0c6-36fe-4ba0-95ec-ba8ff2629b99)

After we enabled all permissions click "Add Role"

We should see the role "Super-User" in the updarted roles table: 

![image](https://github.com/user-attachments/assets/8a67466b-b732-4ae2-8019-67e98477b0f9)


### Configure Departments

The Purpose of departments in osTicket is mainly for ticket "visibility" for example:  
- The "Networking Department" would get assigned network related tickets  
- The "Support Department" Would get assigned tickets like password resets as an example.   

These departments would get assigned tickets that pertain to their department and wouldn't see tickets that are irrelevant 

Lets now create a "SysAdmins" Department

 Navigate to Agents > Departments > click on "Add New Department"

![image](https://github.com/user-attachments/assets/90d97d32-485d-48f2-84b1-2eadf09d20aa)

Lets now create a "SysAdmins" Department

Choose Top-Level Department and name it `SysAdmins` Thats all the configuration for now. click "Create Dept"

![image](https://github.com/user-attachments/assets/64d557f8-0f87-4fb4-a29b-3431560f8e91)






### Configure Teams

Navigate to  Agents > Teams

### Configure Agents

Navigate to Agents > Add New

### Configure Users

Navigate to Users > Add New

### Configure SLA (Service Level Agreement)

Navigate to  Manage > SLA

### Configure Help Topics

Navigate to Manage > Help Topics




