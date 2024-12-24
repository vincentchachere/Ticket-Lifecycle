<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution

In this lab, we navigate the osTicket helpdesk system, following the lifecycle of a ticket from intake to resolution. Using tools like Microsoft Azure, IIS, and Remote Desktop, we manage and operate the system in a real-world scenario.

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (macOS)
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10</b> (21H2)

## Ticket Lifecycle Stages

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

## Lifecycle Stages

### Stage 1. ) Intake - Creating Tickets

- Open osTicket: http://localhost/osTicket/

- Select: `Open a New Ticket`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/673114d4-4c1a-4911-b7e8-da0bf84bfcf8"><br>

<br>
<br>
<br>
  
<ins>Insert the following Ticket Information</ins>:

  - Email Address: `Karen@osticket.com`

  - Name: `Karen Karen`

  - Help Topic: `Business Critical Outage`

  - Issue Summary: `Entire mobile online banking is down`
 
  - Ticket Details: `Customers are reporting they are getting a 404 error when browsing to online banking.`

- Click: `Create Ticket`

*When mobile online banking is down it can lead to major loss in revenue for the company.***

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/d1feaef0-f9a3-4003-8e37-c6762317e266"><br>

<br>
<br>
<br>

### Step 2. ) Assignment and Communication

<ins>Logout of your original user login account, if you haven't already then</ins>:

- Login to osTicket as an Agent: `jane.doe / jane.doe@gmail.com`

*The one you made in the `Post-Install-Config` lab on:* [Step 6.B](https://github.com/vincentchachere/post-install-config)

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/61b97e7e-8775-40a9-b0cf-87b5d10b420d"><br>

<br>
<br>
<br>

<ins>Assigning and Communicating the Ticket Lifecycle</ins>:

- Select: The `Entire mobile online banking is down` Ticket

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/4b5999ab-d140-4fde-ab70-819c3e4e18f6"><br>

<br>
<br>
<br>

<ins>Assigning The Ticket Priority Level<ins>:

- Priority: `Emergency`

  - Type In: `Business Impacting Event`
 
  - Click: `Update`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/user-attachments/assets/ec24788f-97db-4b89-a546-f5090c534665"><br>

<br>
<br>
<br>

<ins>Assigning the Ticket Department</ins>:

- Click: `Department`

  - Select: `System Administrators`

  - Input Details: `Sys Admins responsible for mobile banking infrastructure`
 
  - Click: `Transfer`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/36c0c3af-eef1-42fe-995b-a1434502f81a"><br>

<br>
<br>
<br>

<ins>Assigning the Ticket Team</ins>:

- Assign to: `Jane Doe`

  - Click: `Assign`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/a554032d-af6a-4a58-8b61-4eb41fb8eb68"><br>

<br>
<br>
<br>

<ins>Assigning the Ticket SLA Plan</ins>:

- SLA Plan: `SEV-A`

  - Details: `Business Impacting, Critical Event`
 
  - Click: `Update`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/7e8ed40c-2af1-47b0-9c21-f46559d890f8"><br>

<br>
<br>
<br>

<ins>Verify your ticket information matches the image below and continue to the next step</ins>.

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/b24b24ca-bde3-42cc-bab7-d5b4cd8a036e"><br>

<br>
<br>
<br>

<ins>Observing the Ticket Thread is where you will see the history and updates of the tickets</ins>.

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/24eb9246-f9ab-4d37-b64f-920b9632a609"><br>

<br>
<br>
<br>

<ins>Navigating the Post Reply Box</ins>:

- Input into the Response Text Box: `Coordinating with Sys Admin Team to bring mobile banking back online.`

- Select: `Post Reply`

*The organizaition you work for will determine the type of details you place into the description.*

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifestyle/assets/161680745/1b17a40a-3193-423b-9bdd-201edc1fa24a"><br>

<br>
<br>
<br>

<ins>Notice the message instantly populates inside of the ticket thread</ins>

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/1a3d6911-74ca-4273-8af5-55dc285085b4"><br>

<br>
<br>
<br>

<ins>Observing the Ticket Changes</ins>:

- Go Back To: The `Entire mobile online banking is down` Ticket

*Notice the Priorty and Department sections have been updated.*

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/ea59a152-6bc6-4abf-9cf1-f729f8339c40"><br>

<br>
<br>
<br>

### Stage 3. ) Working the Issue

*On the back end, Jane is working with the System Adminstrator team to resolve the issue.*

### Stage 4. ) Resolution

<ins>Once the issue is resolved, head back to the ticket and update the end user, then</ins>

- Input into the Response Text Box: `Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up.`

- Ticket Status: `Resolved`

- Select: `Post Reply`

<p align="center">
<img width="800" alt="isolated" src="https://github.com/user-attachments/assets/2f9f2fd1-bbba-4e7e-bbce-695ad2e08f38"><br>

<br>
<br>
<br>

<ins>Heab back into your My Tickets tab</ins>:

The ticket should now be on the closed. As you will witness there are no longer any more tickets, since it has been resolved.

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/ecaee293-92df-4ccb-8e5b-67e3cd53334c"><br>

<ins>Observing your Closed Tickets Tab</ins>:

Lastly, if you go to the <ins>Closed Tab</ins> within your <ins>Tickets section</ins>, you will see that the Karen Ticket you resolved is inside there. This lets you confim that you have succesfully resolved that ticket.

<p align="center">
<img width="800" alt="isolated" src="https://github.com/vincentchachere/ticket-lifecycle/assets/161680745/5ae96625-a25d-4e74-9196-3f4502039d84"><br>

☎️ For any questions or just to connect you can message me at: www.linkedin.com/in/vincentchachere
