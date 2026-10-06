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

- Configure Role (for grouping permission)
- Configure Departments (Ticket visibility, help desk vs Sysadmins, vs Networking)
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics
  
<h2>Configure Role (for grouping permission)</h2>

<p>
<img width="600" height="481" alt="image" src="https://github.com/user-attachments/assets/6fab404a-a859-4546-997f-ac74d079c6d4" />
</p>
<p>
In osTicket, configuring roles and grouping permissions is an important part of managing security and controlling what staff members are allowed to do within the help-desk system. A role can be understood as a collection or group of permissions that determines what a particular type of staff member can access and what actions that person can perform. Instead of giving every staff member complete access to the entire osTicket system, an administrator can create appropriate roles and assign permissions based on each employee's responsibilities. This makes the system more organized, secure, and easier to manage.</p>
<br />

<h2>Configure Departments (Ticket visibility, help desk vs Sysadmins, vs Networking)</h2>

<p>
<img width="625" height="323" alt="image" src="https://github.com/user-attachments/assets/a39ad174-7e3f-409b-aba2-64cd51be4efd" />
</p>
<p>
Configuring departments in osTicket is an important part of organizing a help-desk system because departments determine how support work is divided, managed, and accessed by different groups of staff. In a real organization, not every employee deals with the same type of technical problem. For example, a Help Desk team may handle general computer and user-support issues, a Systems Administration team may manage servers and user accounts, and a Networking team may handle network connectivity, switches, routers, wireless access, and other network-related problems. Creating departments in osTicket allows these responsibilities to be separated and helps ensure that tickets are handled by the appropriate team.</p>
<br />


<h2>Configure Teams</h2>

<p>
<img width="653" height="488" alt="image" src="https://github.com/user-attachments/assets/570b08a8-7b44-4338-b8fd-1461bd6aa877" />
</p>
<p>
Configuring teams in osTicket is important because teams allow an organization to group staff members together so they can work collectively on support tickets and specific types of technical problems. In a help-desk environment, individual employees may have different responsibilities, skills, and areas of expertise. Instead of managing every employee separately, teams provide a structured way to organize staff and assign responsibility for resolving tickets.</p>
<br />


<h2>Configure Agents (workers)</h2>

<p>
<img width="661" height="255" alt="image" src="https://github.com/user-attachments/assets/ec40a298-988e-45b6-8de4-bd09eb2704e6" />
</p>
<p>
Configuring agents, sometimes referred to as workers or staff members, is one of the most important steps when setting up and managing an osTicket help-desk system. An agent is a staff member who uses osTicket to perform support-related tasks, such as viewing tickets, responding to customers, assigning tickets, updating ticket information, and resolving technical problems. While customers submit support requests through the ticket system, agents are the employees who investigate those requests and provide solutions</p>
<br />


<h2>Configure Users (customers)</h2>

<p>
<img width="606" height="287" alt="image" src="https://github.com/user-attachments/assets/36a28b45-177c-4940-a83b-615707f67d31" />
</p>
<p>
Configuring users, or customers, in osTicket is an important part of creating a functional help-desk system. While agents are the employees who provide technical support, users are the people who request that support. A user can be an employee, customer, student, client, or any other person who needs assistance from the organization. Configuring users allows osTicket to identify who is requesting help, associate their support requests with the correct person, maintain a history of their tickets, and provide a reliable method of communication between the customer and the support staff</p>
<br />


<h2>Configure SLA</h2>

<p>
<img width="643" height="342" alt="image" src="https://github.com/user-attachments/assets/b9d0d63f-0485-4e9a-9efb-d56a047a40a0" />
</p>
<p>
Configuring an SLA (Service Level Agreement) in osTicket is important because it establishes clear expectations about how quickly support tickets should be responded to and resolved. In a help-desk environment, not every support request has the same level of importance. A minor request, such as asking for help installing a printer, does not necessarily require the same response time as a critical problem, such as a company-wide network outage. SLA configuration allows an organization to define different levels of service and establish time limits for responding to and resolving support requests.

An SLA provides a structured way of managing support performance. Instead of allowing tickets to remain open indefinitely, the organization can establish deadlines and priorities. This helps support staff understand which tickets require immediate attention and which tickets can be handled later.</p>
<br />


<h2>Configure Help Topics</h2>

<p>
<img width="640" height="442" alt="image" src="https://github.com/user-attachments/assets/1063a5b1-0c82-42c4-ab3b-4f9241b48730" />
</p>
<p>
Configuring Help Topics in osTicket is important because Help Topics provide a structured way to identify and categorize the reason a customer is contacting the help desk. When a customer submits a ticket, the support team needs to understand what type of problem or request the customer has. Help Topics make this process easier by providing predefined categories such as Password Reset, Network Problem, Hardware Issue, Software Support, Email Problem, and Account Request.

Without properly configured Help Topics, tickets may arrive at the help desk with little organization. Agents may have to read every ticket manually to determine what type of problem it represents, which can slow down ticket assignment, prioritization, and resolution. Help Topics help turn a large collection of support requests into an organized system.</p>
<br />

