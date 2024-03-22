e<p align="center">
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

### Stage 1.A: Intake - Creating Tickets

<ins>We will create 3 different tickets and there will be 3 parts to Stage 1 (1.A - 1.B - 1.C)</ins>

- Open osTicket: http://localhost/osTicket/

- Select: `Open a New Ticket`

  - Email Address: `Karen@osticket.com`

  - Name: `Karen Karen`

  - Help Topic: `Business Critical Outage`

  - Issue Summary: `Entire mobile online banking is down`
 
  - Ticket Details: `Customers are reporting they are getting a 404 error when browsing to online banking.`

- Click: `Create Ticket`
 
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/673114d4-4c1a-4911-b7e8-da0bf84bfcf8"><br>

***

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/d1feaef0-f9a3-4003-8e37-c6762317e266"><br>

***

### Stage 1.B: Intake - Creating Tickets

- Open osTicket: http://localhost/osTicket/

- Select: `Open a New Ticket`

- <ins>Create your 2nd Ticket</ins>

  - Email Address: `Ken@osticket.com`

  - Name: `Ken Ken`

  - Help Topic: `Personal Computer Issues`

  - Issue Summary: `Entire Account Dept Adobe Reader Not Working`
 
  - Ticket Details: `Ever since the upgrade last night, nobody in accounting has been able to use adobe reader.`

- Click: `Create Ticket`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/54f22c6d-aaac-4aa7-92d5-c34925ed2f2d"><br>

***

### Stage 1.C: Intake - Creating Tickets

- Open osTicket: http://localhost/osTicket/

- Select: `Open a New Ticket`

- <ins>Create your 3rd and Final Ticket</ins>

  - Email Address: `Karen@osticket.com`

  - Name: `Karen Karen`

  - Help Topic: `General Inquiry`

  - Issue Summary: `When are we getting a hardware refresh`
 
  - Ticket Details: `Most of my department is having issues with their current tablets, we need this ASAP. Please provide info.`

- Click: `Create Ticket`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/5555abdd-f15e-49d6-9dbc-6ce3844088a2"><br>

***

### Step 2: Assignment and Communication

*If you do not see all your tickets then you will need to remake then, for some reason it does not load/refresh properly sometimes.*

- Login to osTicket as an: `Agent (User: jane.doe / jane.doe@gmail.com)`

  - The one you made in the 'Post-Install-Config Lab' on [Step 6.B](https://github.com/vincentchachere/post-install-config)

- Click: The `When are we getting a hardware refresh` Ticket

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/61b97e7e-8775-40a9-b0cf-87b5d10b420d"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/42b4bdfe-80d3-4529-8d77-9774eaab93b3"><br>
***

*When mobile online banking is down it can lead to major loss in revenue for the company.*

- Priority: `Emergency`

- Department: `System Administrators`

  - Details: `Sys Admins responsible for mobile banking infrastructure`
 
  - Click: `Transfer`

- Assigned to: `Jane Doe`

- SLA Plan: `SEV-A`





- `Business Impacting, Critical Incident`

- Response Text ox: `Coordinating with Sys Admin Team to bring mobile banking back online.`

- Select: `Post Reply`

<img width="1511" alt="isolated" src=""><br>
***
<img width="1511" alt="isolated" src=""><br>
***
<img width="1511" alt="isolated" src=""><br>
***
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

Congratulations! You have created and resolved your first few tickets!
