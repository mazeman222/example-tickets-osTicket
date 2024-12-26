<p align="center">
<img src="imagesl/Screenshot%202024-12-25%20042807.png">
</p>

<h1>osTicket - Example Tickets osTicket</h1>
Here I will outline from beginning to resolution with the open-source help desk ticketing system osTicket.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of what is needed</h2>

- Desktop/Laptop
- Azure/AWS/Google Account (When you signup with Microsoft Azure free tier, you get a $200 credit.)
- Internet Information Services (IIS) Manager
- Remote Desktop Connection

- Login to the "admin portal" of osTicket which can be found here localhost/osTicket/scp/login.php
  Once logged in then click on the "admin panel > agents > departments". You will want to make sure that the department that you have created before in the "parent" box it is selected as "top level department". You can log out of the "admin" account for now.

- Go to the search bar of any browser and type in: localhost/osTicket
<img src="imagesl/Screenshot%202024-12-26%20021148.png">
When you click on the "open a new ticket button, you will be brought to this window:
<img src="imagesl/Screenshot%202024-12-25%20043734.png">
In this window you want to make sure to fill out the informaion and then click "create ticket" when you are finished. Go back to "localhost/osticket/scp/login.php" and login as "one of the agents" that you have created earlier. In the agent panel check the ticket that you have just created and click on the "ticket" and examine its properties. When you are satisfied you can close the ticket and it will be deleted from the "agent panel".

- Now you have have went through the lifecycle of a ticket in osTicket.
