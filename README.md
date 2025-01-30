![image](https://github.com/user-attachments/assets/12d8af4e-91e8-4fe3-b751-c2f78d1132d7)


# OsTicket-Post-Install-Config

This demonstrates the necessary changes we make to configure osTicket so it can be used as a proper ticketing system.


 ## Environments and Technologies Used


* Microsoft Azure (Virtual Machines/Compute)
* Remote Desktop Connection
* osTicket

## Operating Systems Used

Windows 10 Pro (21H2)

## Configuration Steps

After the Installation of the OS Ticket, we will need to configure Roles for grouping permissions.


First, at the top right panel, you can see the Admin Panel click on this tab ,now navigate to > Agents > Roles and add a new role. Name this Supreme Admin. They will need access to all components. Next, move to permissions and select all boxes, as the Supreme Admin will be allowed access to all areas in Tickets/ Tasks /and Knowledgebase.Once complete, add the role, and now a new role for Supreme Admin has been added.

![image](https://github.com/user-attachments/assets/f7a8862f-e471-4f45-8588-0dd3af3bb709)

![image](https://github.com/user-attachments/assets/32205b3e-952f-473c-9c55-fb744822792b)

![image](https://github.com/user-attachments/assets/a7bdf5d9-c51a-4969-87c0-9ff8a6f30383)

![image](https://github.com/user-attachments/assets/aad6cd84-1544-43eb-9226-7bc77bd361b9)

![image](https://github.com/user-attachments/assets/7a8bfe0f-182a-4dd9-9036-242827290abe)

![image](https://github.com/user-attachments/assets/8e0b6ed0-445a-41f9-b558-f8f4084804de)


Adding new roles and Permissions in Agents under the  Admin Panel

![image](https://github.com/user-attachments/assets/2abadd0d-8282-4da2-a000-943850856c73)


After the Installation of OS Ticket, we will also need to configure departments. This will be for Ticket visibility. Help desk vs SYSAdmin, VS Networking. We will go to Departments and add new ones. Now in Add new Department under parent select Top-Level- Department and next name this Sysadmins and leave all settings the same. Scroll down and create dept. And now we have added SysAdmins to the list of Departments.

![image](https://github.com/user-attachments/assets/29e9668e-c0d3-4da3-be9e-e7efc1ae710a)

![image](https://github.com/user-attachments/assets/e2241f2a-bd3c-4034-953d-b12022923981)

![image](https://github.com/user-attachments/assets/d7b1792a-a61e-4608-953e-ef05d63b92c9)


Once the Departments are set up, we will configure Teams. From the same screen, navigate to the Teams tab and add a new team. Name this team Online Banking and create it. We will also have to implement and allow anyone to create a heat ticket without having to register.

![image](https://github.com/user-attachments/assets/20d90f20-385a-4f1e-b019-2177787c7576)

![image](https://github.com/user-attachments/assets/4e4c7d94-fe43-4cb0-b377-0fa745c6b85d)


![image](https://github.com/user-attachments/assets/b0bc62e2-348a-47a6-b8f5-bac217072d79)


## NOTE
Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Require registration and login to create tickets 

![image](https://github.com/user-attachments/assets/3278a715-c65b-445e-bb2f-3472cfdf5077)


Now, we will create and configure agents /workers. On the agents tab, click Add New. For this purpose, we will add two Agents with different profiles. The first Agent is James, who is a Supreme Admin and has access to all as an Admin. On the account, fill out your first and last name as well as an email address. Now, create a username and set a password. Once you choose a password, uncheck the change at the next login.

![image](https://github.com/user-attachments/assets/24e45901-5b85-4bc1-ac6c-d68bf91f046f)

![image](https://github.com/user-attachments/assets/ce956589-6670-4b9d-a289-d0dfb60d13fa)

Make sure to uncheck 

![image](https://github.com/user-attachments/assets/02816d93-26f4-4339-87ef-60174a9fecd7)

Then Add the Agent's Password and Uncheck Don't Require Password Change for the Purpose of the project

![image](https://github.com/user-attachments/assets/33e5f5e3-930b-4840-b101-33f6ac32289c)


Next, we will go through the Access tab On the drop-down menu select SysAdmin and then select Supreme Admin. Under Permissions make sure all tabs are selected. Finally, under the Teams tab on the drop-down menu select online banking.

![image](https://github.com/user-attachments/assets/d04b42ee-4b6c-4906-abc0-8de9e8dc79da)

![image](https://github.com/user-attachments/assets/da5cf048-efdb-477b-8ea6-679ec7bc2eb6)

![image](https://github.com/user-attachments/assets/1c1a3dfb-39f1-43ae-b373-a9db9a1d3882)

Then go back to Agents and Recreate another 

The next Agent will be Alexis with limited access as a worker. From the Agents tab click on add new. Just as before fill out all the information and set a password. On the next tab under the drop-down select support and now view only for the access. Now the tabs for permissions and Teams we will leave as is and created. Once you create you can now see both new agents are added.

![image](https://github.com/user-attachments/assets/e3a307b0-fdaa-4e61-9710-8e0159265503)


Set new password

![image](https://github.com/user-attachments/assets/462f51d4-f5bb-431f-aaa7-a5e78784ff56)


Make sure to uncheck 

![image](https://github.com/user-attachments/assets/02816d93-26f4-4339-87ef-60174a9fecd7)

![image](https://github.com/user-attachments/assets/5db6ba33-3866-4e13-9d68-08ef82651455)

Then Add the Agent's Password and Uncheck Don't Require Password Change for the Purpose of the project then Set

![image](https://github.com/user-attachments/assets/33e5f5e3-930b-4840-b101-33f6ac32289c)

Then Access. We give Alexis Limited Access to View Only:

![image](https://github.com/user-attachments/assets/f3092e32-cbdd-4ac0-aaf9-cc04af70702e)

Then Leave Assigned Teams as it is. Then select Create

![image](https://github.com/user-attachments/assets/88e03b74-9b8c-43d3-bfd0-a080b5315bef)

![image](https://github.com/user-attachments/assets/77d446a4-b4cf-4340-bee8-5a0cca610a13)

BOTH AGENTS CREATED

![image](https://github.com/user-attachments/assets/bccf4d28-59e4-4144-b9db-ed6c9b387698)


Configure Agents (workers)
Admin Panel -> Agents -> Add New

We will also have to add Users/ Customers. On the top right select Agent panel. Once there select users and then ADD user. Fill out end user/customer info and tap add user. Once done you can see user was added.

![image](https://github.com/user-attachments/assets/45cacef1-68d0-4945-8d7a-31315a87ae80)

Then Select User

![image](https://github.com/user-attachments/assets/a01fc1e6-3a66-4ef0-b4b6-2c39a33c7766)

The Add User

![image](https://github.com/user-attachments/assets/5d82b63d-1c90-4135-b73e-19d802b2855e)

![image](https://github.com/user-attachments/assets/a59410a4-a0ad-4e2f-8703-b8b313d28a18)

Then select Add User

![image](https://github.com/user-attachments/assets/27b9b2e9-4acb-47e3-aa0a-6017cb82f0cc)

Configure SLA (SLA Meaning, how much time you have to do a specific task)
Admin Panel -> Manage -> SLA


Once the steps above are created we will now need to set SLA priorities. These will dictate what is most important and how long a Help desk will have to resolve customer issues. Now we are back in the Admin Panel top right select agent and this will switch to Admin. Select manage and then SLA. We will create three different SLA groups. SEV-A with a High importance and needed response time of within one hour of ticket request with a 24/7 response time.SEV-B with a four-hour response time and also with a 24/7 response time. And last but not least SEV-C with a response time of eight hours and only worked during a MON-Friday 8am-5pm with US holidays. Now once all SLA's are added they are now visible in the SLA plan.


First Select Admin Panel:

![image](https://github.com/user-attachments/assets/11ce2c16-f7f6-4f33-862f-3560a415a71e)

Select Manage 

![image](https://github.com/user-attachments/assets/0188354b-9c55-4f91-8fe4-124e5b7abba6)

Then select SLA

![image](https://github.com/user-attachments/assets/c4d19b23-7ddf-4c99-ac28-4c3d75b6b9f1)

![image](https://github.com/user-attachments/assets/2ed298ad-2c93-47ed-ad14-ff685b46def0)


Sev-A (Grace Period: 1 hour, Schedule: 24/7) NOTE: A REALLY BAD PROBLEM

![image](https://github.com/user-attachments/assets/30d4ad88-217d-4ead-9085-03cdd1883658)

Then ADD 

![image](https://github.com/user-attachments/assets/32fdad3b-d532-49f9-bdd7-1f46706f3228)

Sev-B (Grace Period: 4 hours, Schedule: 24/7) NOTE: BAD PROBLEM

![image](https://github.com/user-attachments/assets/2d0d5f46-8723-4a09-ae7d-b24e4ec894fd)

THEN ADD

![image](https://github.com/user-attachments/assets/5e8e7d1b-7576-44e9-8304-e034075cd664)

Sev-C (Grace Period: 8 hours, Business Hours) NOTE: NOT A BAD PROBLEM 

![image](https://github.com/user-attachments/assets/2f5a114f-8436-426d-b934-857a5b9ac253)

THEN ADD

![image](https://github.com/user-attachments/assets/f0b3f188-c6dc-4be6-896b-06539a48dd6b)


Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other

Finally, Help Topics need to be created to help users select an appropriate category that describes their problem so that Agents get an idea of what problem is described in the ticket. To make a new Help Topic, enter the Admin panel and open the Manage menu. Click on Help Topics and click on Add New Help Topic. In this case, We will add the following in order to use later for when we create new tickets to resolve: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request.

![image](https://github.com/user-attachments/assets/08ca3d29-eac1-4eb9-95fd-751b6a75b1a9)

![image](https://github.com/user-attachments/assets/8feea665-051a-4c67-a240-05040ef20dc1)


First for Business Critical Outage

![image](https://github.com/user-attachments/assets/ee22802f-3fce-4769-a9e4-ff0f45d39bca)

Then select Add Topic

GO back to Help Topics and repeat

Personal Computer Issues

![image](https://github.com/user-attachments/assets/76e03a8d-ed8b-4c26-8d39-a51dcfe28c6e)

![image](https://github.com/user-attachments/assets/f4a30348-9a51-4094-9c83-e98e012323ca)


Password Reset

![image](https://github.com/user-attachments/assets/bf81a280-a860-4da1-885e-be6e6775c346)


Other

![image](https://github.com/user-attachments/assets/c87757ee-b730-4595-b600-c52034c7522a)


All the Tickets Created

![image](https://github.com/user-attachments/assets/bcf276bd-7c44-460b-8503-f55297366bf8)


## osTicket Configurations are Complete

Now that the configurations have been set in place, we can now utilize osTicket as a proper ticketing system. We can create tickets and be able to trigger them as if I were in a real environment.




