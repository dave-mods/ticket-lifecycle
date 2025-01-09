<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket
  
<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

We will start by creating a ticket on the osTicket end user side. Use Ken's email we setup and the issue we are going to make a ticket about is "entire mobile/online banking system is down". We will pick the wrong Help Topic so we can chage it later with a agent inside osTicket. Select "Report a problem" from the menu. Then fill in the comment box with something like this and submit the ticket.
![image](https://github.com/user-attachments/assets/020ba7c1-726c-4e97-be4d-75623db57304)

Next we will login as John on the agent login.
![image](https://github.com/user-attachments/assets/ab74ccde-6e72-415a-8365-bccf8df439a6)
![image](https://github.com/user-attachments/assets/90d6b4d8-622d-4955-851b-5349a488b5b5)

As John we will open the ticket we subbmitted as Ken and view it. So because Ken only put it as Report a Problem the ticket Priority defaulted to Normal, and the SLA defaulted to Default SLA. We now have to review the ticket and make any adjustments as needed.
![image](https://github.com/user-attachments/assets/3bad384b-1a7d-4270-9848-efcfddb52476)

Here we will change the SLA plan to Sev-A. Due to online banking being down that needs to be addressed right away. We will add in a note when we change the Sev so we know its a high priorty and why.
![image](https://github.com/user-attachments/assets/3db4c888-db5e-42ef-b8a5-9f5369f15eb2)

We will then change the Help Topic from Report a problem to Report a problem/ Business critical outage
![image](https://github.com/user-attachments/assets/0236f464-185e-47e8-9d5c-682cdb0d0eb3)

Then we can change Priority on the ticket to Emergency.
![image](https://github.com/user-attachments/assets/48041873-a469-4f5b-81c6-97c15ba95f93)

We cnah change the Assigned to from unassigned to Online Bnaking.
![image](https://github.com/user-attachments/assets/2d3b8928-1849-440a-9076-127a753219e5)

Now we can see on the ticket all the changes we have been doing. They appear as notes so we cna keep track of any changes made.
![image](https://github.com/user-attachments/assets/0cbe93c3-4f85-4650-9731-baf698ef4a69)

If we go back to the Tickets tab we can see the Priority and Assigned To have both been updated.
![image](https://github.com/user-attachments/assets/fcee5e3a-c800-4a8a-a476-ae8bf128c0ea)

So if we go back into the ticket and go down to the notes and we have "worked through" the problem we will post a update here for everyone to see.
![image](https://github.com/user-attachments/assets/4eb542ed-2b90-44bb-bacd-a5246275a94c)

Now that the ticket is done and the customer has confirmed that they can now access online banking again we can change the ticklet status at the bootom to Resolved.
![image](https://github.com/user-attachments/assets/75fc0cc4-d989-49fc-b3c7-b9589053dccb)

The resolved ticket is now gone off the Open Ticket list. If you need to find the ticket again it can be found under the closed ticket tab.
![image](https://github.com/user-attachments/assets/9eafa631-081e-42b6-bf10-4e9f49ffa672)
![image](https://github.com/user-attachments/assets/80a41453-20e5-4510-9a46-6b801efa8095)



osTicket: Creating and Working Tickets is now Complete!
We've successfully gone through the life cycle of a ticket from creation to resolution, made changes to the tickets when necessary like assigning the tickets, changing the SLA (Service Level Agreement), and commenting to create a thread of clear communication! 
