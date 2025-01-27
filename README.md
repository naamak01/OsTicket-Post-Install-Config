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

After Installation of OS Ticket we will need to configure Roles for grouping permissions.


First on the top right panel you can see the Admin Panel click on this tab ,now navigate to > Agents > Roles add a new role. Name this Supreme Admin. They will need access to all components. Next move to permissions and select all boxes as the Supreme Admin will be allowed access to all areas areas in Tickets/ Tasks /and Knowledgebase.Once complete add role and now, a new role for Supreme Admin was added.

![image](https://github.com/user-attachments/assets/f7a8862f-e471-4f45-8588-0dd3af3bb709)

![image](https://github.com/user-attachments/assets/32205b3e-952f-473c-9c55-fb744822792b)

![image](https://github.com/user-attachments/assets/a7bdf5d9-c51a-4969-87c0-9ff8a6f30383)

![image](https://github.com/user-attachments/assets/aad6cd84-1544-43eb-9226-7bc77bd361b9)

![image](https://github.com/user-attachments/assets/7a8bfe0f-182a-4dd9-9036-242827290abe)

![image](https://github.com/user-attachments/assets/8e0b6ed0-445a-41f9-b558-f8f4084804de)


Adding new role and Permissions in Agents under Admin Panel

![image](https://github.com/user-attachments/assets/2abadd0d-8282-4da2-a000-943850856c73)


After Installation of OS Ticket we will also need to configure departments.This will be for Ticket visability. Help desk vs SYSAdmin , VS Networking. We will go to Departments and add new. Now in Add new Department under parent select Top-Level- Department and next name this Sysadmins and leave all settings the same. Scroll down and create dept.And now we have added SysAdmins to the list of Departments.

![image](https://github.com/user-attachments/assets/29e9668e-c0d3-4da3-be9e-e7efc1ae710a)

![image](https://github.com/user-attachments/assets/e2241f2a-bd3c-4034-953d-b12022923981)

![image](https://github.com/user-attachments/assets/d7b1792a-a61e-4608-953e-ef05d63b92c9)


Once the Departments are setup we will now configure Teams. From the same screen now navigate to the Teams tab and now add a new team. Name this Online Banking and now create. We will also have to implement and allow anyone to create a heat ticket so they will not have to register.









