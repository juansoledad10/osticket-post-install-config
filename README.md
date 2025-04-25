# osticket-post-install-config
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

- Create User
- Login in as Admin
- Set Up SLAS
- Login End-User

<h2>Configuration Steps</h2>

<p>
<img width="1437" alt="Screenshot 2025-04-23 at 9 49 27 PM" src="https://github.com/user-attachments/assets/90d0d31b-c0e5-4a21-a10f-53a02451f29f" />
Now that we can start using the ticketing system, we can go to this URL and sign in to our admin account, which will allow us to configure roles and permissions as well as create different departments with different roles 
</p>
<p>
<img width="1440" alt="Screenshot 2025-04-24 at 7 39 27 PM" src="https://github.com/user-attachments/assets/060d7b2e-480b-49ff-a1d5-aa242f1c5207" />
Once you successfully log in to the admin dashboard, we can configure settings on the back-end for the osTicket. We can also switch from the admin panel and agent panel on the top right, and once we switch to the  agent panel, that will allow us to resolve the tickets as an agent or as a worker in this example 
 <img width="1440" alt="Screenshot 2025-04-24 at 7 49 36 PM" src="https://github.com/user-attachments/assets/b87c2eac-b7d7-4bdc-ad8c-9b0e85b362dd" />

Now in this step, we are adding a new role which will have permission to view and access all the system and also be able to make changes. You will click the add role button circled above, and then name it Supreme Admin for this example, and select all the permissions. After that, we are going to create a new department and call it SysAdmins
<img width="1440" alt="Screenshot 2025-04-24 at 7 52 43 PM" src="https://github.com/user-attachments/assets/e0a1d4e7-0d42-420a-8dc6-fdd490f6c10b" />
Also, we can create specific teams that, for a work environment, could be a good way to organize people in similar departments to help keep a better track and it organized, so, for this example, we will make it online banking 
<img width="1440" alt="Screenshot 2025-04-24 at 7 54 49 PM" src="https://github.com/user-attachments/assets/a63861da-430c-4029-bca9-e52643d8d7f5" />
We will need to then create the agents that, in this practice, will be the agent accounts that will be the ones solving the tickets 
<img width="1440" alt="Screenshot 2025-04-24 at 8 00 43 PM" src="https://github.com/user-attachments/assets/bc1378f4-e9a6-436b-9681-a2e48e6ce224" />
For this next step, we are going to create users, end-users to be exact, and they will be the ones who create the tickets when they need help with their IT issues. We are switching over to the agent panel, it should look like this once you click the top right 
<img width="1440" alt="Screenshot 2025-04-24 at 8 07 43 PM" src="https://github.com/user-attachments/assets/2a716430-fe69-470c-abbc-66354341c052" />
Now we are going to click add user, and you will need an email and first and last name, and for this example, I'm using a random name. Just make sure you save it in notes so you don't lose track of everything. Once you have created the user, we will need to switch over to the admin panel again because now we are going to establish the SLA's for our ticketing system
<img width="1440" alt="Screenshot 2025-04-24 at 8 23 33 PM" src="https://github.com/user-attachments/assets/e0c8e5be-3ba4-4c81-ad25-ad28bf98264d" />
Here we can create an SLA that follows the rules and guidelines a corporation has, and how SLA helps emphasize a business perspective on issues. For this example I will be making 3 SLA SevA- which is the most critical and will have a 1 hour grace period with a 24/7 schedule, then there will be Sev-B which will have a 4 hour grace period with also a 24/7 schedule, and finally there will be Sev-C which has a 8 hour grace period with a 25/7 schedule which is just normal business hours. It should look like this when completed correctly
<img width="1440" alt="Screenshot 2025-04-24 at 8 29 12 PM" src="https://github.com/user-attachments/assets/48218f3d-a778-4a11-811f-1b40699438e8" />
Lastly will be adding help topics. These are very useful for both the agents and the admins.
<img width="1440" alt="Screenshot 2025-04-24 at 8 33 02 PM" src="https://github.com/user-attachments/assets/71ccd17b-4d01-4cba-99c3-cc6546b0f989" />
It helps everyone be more specific when creating the ticket, because if you pick the correct help topic, it can help the IT agent be well aware of what type of issue he is helping solve. Here are some examples that can be created to help be more specific when someone has issues and some that are very common as well

<img width="1440" alt="Screenshot 2025-04-24 at 8 34 06 PM" src="https://github.com/user-attachments/assets/a9d12d07-46c0-4bba-b0f2-df2d5ab0b0e1" />
<img width="1440" alt="Screenshot 2025-04-24 at 8 34 42 PM" src="https://github.com/user-attachments/assets/2e75e01b-a618-4a84-8a52-1d3d7dd5607c" />
<img width="1440" alt="Screenshot 2025-04-24 at 8 35 22 PM" src="https://github.com/user-attachments/assets/250dda0b-3a22-43d7-8e91-507ea47ce146" />
<img width="1440" alt="Screenshot 2025-04-24 at 8 35 48 PM" src="https://github.com/user-attachments/assets/88686dde-56f5-4a10-87f8-dca7cba272a3" />
<img width="1440" alt="Screenshot 2025-04-24 at 8 36 11 PM" src="https://github.com/user-attachments/assets/ec74ef4c-8eab-4a41-90b8-65b4d40876ff" />
At this point, all the help topics are set up, SLA's are established, end users were created and registered, as well as the agent who can start and finish with a ticket. Here we see all the help topics after we created the ones seen above 
