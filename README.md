<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source helpdesk ticketing system osTicket.<br/>

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used

- macOS
- Windows 10</b> (21H2)

## Ticket Lifecycle Stages

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

## Lifecycle Stages

### Stage 1: Intake - Creating a Ticket

- Open osTicket: http://localhost/osTicket/

- Select: `Open a New Ticket`

  - Email Address: `Karen@osticket.com`

  - Name: `Karen Karen`

  - Help Topic: `Business Critical Outage`

  - Issue Summary: `Entire mobile online banking is down`
 
  - Ticket Details: `Customers are reporting they are getting a 404 error when browsing to online banking`

- Click: `Create Ticket`
 
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/673114d4-4c1a-4911-b7e8-da0bf84bfcf8"><br>

***

 <img width="1511" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/67e6a10d-1a77-41e0-9f82-ca91ed18f91a"><br>

***

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/a4ea2ede-618c-4095-a03a-a67bb9f2f3a7"><br>

***

### Step 2: Assignment and Communication

- Sign into osTicket as an Agent

  - We created jane.doe in previous tutorial, log in with those credentials. 

  - Select the ticket we created in Step 1.

 <img width="1511" alt="isolated" src=""><br>

***

- Priority: Emergency

- Mobile online banking down can lead to losses in revenue for the company

- Assigned to: Jane Doe

- SLA Plan: SEV-A

- Business impacting, critical incident

- Department: System Administrators 

- Sys Admins responsible for mobile banking infrastructure

- Response text box: Coordinating with Sys Admin Team to bring mobile banking back online.

- Select Post Reply

<img width="1511" alt="isolated" src=""><br>

***

### Stage 3: Working the Issue

- On the back end, Jane is working with the System Adminstrator team to resolve the issue.

### Stage 4: Resolution
     
- Once the issue is resolved, head back to the ticket and update the end user.

- Response text box: Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up.

- Ticket Status: Resolved

- Select Post Reply

- The ticket should now be on the "closed" tab since it has been resolved.

<img width="1511" alt="isolated" src=""><br>

***

Congratulations! You have created and resolved your first ticket!``
