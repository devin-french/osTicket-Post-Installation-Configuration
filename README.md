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



<h2>Configuration Steps</h2>

<p>
<img width="1280" alt="Screenshot 2024-12-17 at 7 47 14 PM" src="https://github.com/user-attachments/assets/ef570d41-fb56-444c-a6e9-3ce70aa93c53" />
<img width="1280" alt="Screenshot 2024-12-17 at 8 09 37 PM" src="https://github.com/user-attachments/assets/6b4bf3ea-d43f-4ccb-8c72-a843783c135a" />
</p>
<p>
After installing osTicket, configure it by switching between the Admin and Agent panels, which have different settings. The panel in use is indicated at the top right ("Agent Panel" means you're in the Admin panel). Start by creating a new role called "Supreme Admin”, then click all available permissions. To do this, go to the Admin panel, open the Agents menu, click on Roles, and then create a new role.
</p>
<br />

<p>
<img width="1280" alt="Screenshot 2024-12-17 at 8 13 07 PM" src="https://github.com/user-attachments/assets/c6d52025-02df-449f-ba47-e17dd9e8e5b2" />

</p>
<p>
Next, create a new Department for the System Administrators. In the Admin panel, navigate to the Agents menu and select Departments to add a new department in osTicket.
</p>
<br />

<p><img width="1280" alt="Screenshot 2024-12-17 at 8 19 20 PM" src="https://github.com/user-attachments/assets/d90c9ad5-011a-41b1-92e7-4e6a772bc79d" />
<img width="1280" alt="Screenshot 2024-12-17 at 8 27 55 PM" src="https://github.com/user-attachments/assets/1a12878d-6b85-4910-9d1e-8788d5e4fffc" />
<img width="1280" alt="Screenshot 2024-12-17 at 8 29 27 PM" src="https://github.com/user-attachments/assets/95e6d340-dd0b-461e-bac4-06199b5065c8" />
<img width="1273" alt="Screenshot 2024-12-17 at 8 33 22 PM" src="https://github.com/user-attachments/assets/9460632d-71a6-4ce3-b845-8559249382a5" />
<p>New agents will have to be created so they can take tickets that come to the queue. In order to create new agents, click on the Admin panel and open the Agents menu. Click “add new agent”  and create the account credentials for each new agent. In this case, Jan and Jon Doe are created.

</p>
<img width="1280" alt="Screenshot 2024-12-17 at 8 37 58 PM" src="https://github.com/user-attachments/assets/50400ddb-f38b-4bd8-bca7-285134ea017a" />

New users will be created so they can create tickets so that the agents can receive and respond to them. To create new users, click the Agents panel and open the Users menu. Click on Add User and create the account credentials needed  for each new user. In this case, Karin and Ken have been created.


<img width="1280" alt="Screenshot 2024-12-17 at 8 55 08 PM" src="https://github.com/user-attachments/assets/e5f306fb-aa61-42f9-b4a5-eb2cbeee38e3" />

Service Level Agreements (SLAs) will have to be made in order to categorize tickets according to their level of severity. To make new SLAs, click Admin panel and open the Manage menu. Click on SLA and create any needed SLAs. In this case, SEV-A, B, and C have been created to categorize tickets that need to be resolved within 1 hour, 4 hours, and 8 hours.


<img width="1280" alt="Screenshot 2024-12-17 at 8 58 22 PM" src="https://github.com/user-attachments/assets/bd7655ea-9a7e-4a4a-93e9-ffc53793aadc" />


Finally, Help Topics need to be created to help users choose the appropriate category that describes their problem so Agents can get an idea of what problem is described in the ticket. To make a new Help Topic, click Admin panel and open the Manage menu. Click on Help Topics and then on Add New Help Topic. In this case, I’ve  added the following in order to use later for when I create new tickets to resolve: Business Critical Outage, Personal Computer Issues, Equipment Request, and Password reset
